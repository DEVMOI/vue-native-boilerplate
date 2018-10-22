<template>
  <Greeting :Heading='Heading'/>
</template>
 <script>
 import Greeting from './src/components/Greeting';
 export default {
   name: 'App',
   components:{
     Greeting
   },
   data(){
     return{
       Heading:'A Vue Native Boilerplate'
     };
   }
 }
 </script>
 
<style></style>
