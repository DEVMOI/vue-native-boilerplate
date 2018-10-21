<template>
  <HelloWorld :Heading='Heading'/>
</template>
 <script>
 import HelloWorld from './src/components/HelloWorld';
 export default {
   name: 'App',
   components:{
     HelloWorld
   },
   data(){
     return{
       Heading:'A Vue Native Boilerplate'
     };
   }
 }
 </script>
 
<style>

</style>
