<template>
  <div class="box">
      <h1> Hello People</h1>
      <p>{{parag}}</p>
      <a :href="newsweek">Week<br><br></a>
      <button @click="helloWorld">Click me<br></button>
  </div>
</template>

<script>
export default {

    data(){
        return{
            parag:"This is the week's news",
            newsweek:"https://www.newsweek.com/",
        }
    },
    methods:{
         helloWorld(){
        console.log("Hello World!")
    }
    }
   
}
</script>

<style>

</style>