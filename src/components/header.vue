<template>
    <header>
       <h1> DATA RETRIEVAL SYSTEM</h1>
       <Button text="Add User" color="green"/>
    </header>
</template>
<script>
import Button from "./button"
export default {
    name: "Header",
    props: {
        title: String,
        
    },
    components:{
        Button,
    }


}
</script>
<style scoped>
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom:20 px;
}

</style>