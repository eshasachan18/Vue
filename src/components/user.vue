<template>
<div class="user">
    <h3>{{task.text}}</h3>
    <i class="fas fa-times"></i>
    </div>
</template>
<script>
export default {
    name: 'User',
    props: {
        user: Object
    }
}
</script>
<style scope>
.fas{
    color:red;
}
</style>