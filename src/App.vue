<template>
  <div>
    <first-component />

   <router-link to="contact">Contact Us</router-link>
    <router-view />
  </div>
</template>

<script>
import FirstComponent from './components/FirstComponent.vue'
export default {
  components: { FirstComponent },

}
</script>

<style>
.box{
  background-color: rgb(165, 231, 165);
}

</style>
