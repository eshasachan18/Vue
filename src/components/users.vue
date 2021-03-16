<template>
    <div :key="user.id" :v-for="user in users">
   
    <User :user="user"/>
     </div >
</template>
<script>
import User from "./user.vue"

export default {
    name:'Users',
    props:{
        users:Array,
    },
    components: {
        User
    }
}
</script>