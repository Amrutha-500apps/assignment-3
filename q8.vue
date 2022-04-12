<template>
    <div>
    <h3>UI with p-tag</h3>
    <p @click="result()">p-tag</p>
    <textarea id="sample"></textarea>
    </div>    
</template>
<script>
export default{
    name:"amruWR2",
    data(){
        return{
            text:"",
        }
    },
        methods:{
          result(){
              this.text = document.write("" + document.grtElementById("sample").value);
          },
        }
}
</script>
