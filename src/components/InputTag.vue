<script>
    export default {
        data(){
            return{
                currentValue: "",
                tags: [],
            }
        }
    }
</script>

<template>
    <div class="inputTag">
    <div class="tags">  
        <div class="tag" v-for="(tag, index) in tags" :key="index">
        
        </div>
    
      </div>
    <input type="text">
        
    </div>


</template>

<style scoped>

</style>