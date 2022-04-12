<template>
    <div>
        <p>{{name}}</p>
        <button @click="errorhandling()">click</button>
    </div>    
</template>
<script>
export default {
    name:"NamE",
    methods: {
        errorhandling(){
         try{
             this.test=this.value*45;
             console.log("test",this.value);
            }
         catch{
             console.log("error handled");
            }
        }
    }
}
</script>
