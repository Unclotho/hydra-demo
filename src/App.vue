<template>
  <div id="app">
    <div class="arrWrapper">
      <Layout/>
    </div>
  </div>
</template>

<script>
import { onMounted } from 'vue'
import Layout from './components/Layout.vue'
export default {
  components: {
    Layout
  },
  setup(){
    onMounted(()=>{
      
    })
  }
}
</script>

<style>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;

    -webkit-touch-callout:none;  
    -webkit-user-select:none;  
    -khtml-user-select:none;  
    -moz-user-select:none;  
    -ms-user-select:none;  
    user-select:none; 
}
*::before, *::after{
    box-sizing: border-box;
}
h1,h2,h3,h4,h5,h6{
    font-weight: normal;
}
a{
    color: inherit;
    text-decoration: none;
}
ul,ol{
    list-style: none;
}
table{
    border-collapse: collapse;
    border-spacing: 0;
}
button{
    border: 0px;
    background: none;
}
input{
  border: 0;
  background: none;
  outline: 0;
}
body{
  background: #000;
  color: white;
}
body::-webkit-scrollbar{
    display: none;
}
.appWrapper{
    width: 100vw;
    height: 100vh;
    display: flex;
    position: absolute;
}
</style>
