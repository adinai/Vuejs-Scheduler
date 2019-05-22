<template>
<div>
    <form>
        <input type="text" name="title" placeholder="Schedule Your Day...">
        <input type="submit" value="Add" class="btn"> 
    </form>
</div>
</template>


<script>
export default{
    name: "AddTodo"
}
</script>


<style scoped>
form{
    display: flex;
}

input[type="text"]{
    flex: 10;
    padding: 5px;
    margin-top: 20px;
    margin-bottom: 20px;
}

input[type="submit"]{
    flex: 2;
    margin-top: 20px;
    margin-bottom: 20px;
}

</style>