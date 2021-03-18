<template>
<div class="user">
    <h3>{{user.text}}  
         
        <!-- <button @click="$emit('delete-user', user.id)" :style="{background:color}" class="delbtn">del</button>-->
        <i @click="$emit('delete-user', user.id)" class="fas fa-times"></i>
        
    </h3>
</div>
</template>
<script>

export default {
    name: 'User',
    props: {
        user: Object
    },
    
    components:{},

}
</script>
<style scope>
.fas {
  color: red;
}
.user {
  background: #f4f4f4;
  margin: 5px;
  padding: 10px 20px;
  cursor: pointer;
}
.task.reminder {
  border-left: 5px solid green;
}
.user h3 {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
</style>
