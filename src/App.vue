<script>

 import AppHeader from './components/AppHeader.vue'

export default {
  components: {
    AppHeader,

  },
  data(){
      return{

      }
    },
    methods: {

    },
    mounted() {

    }
  }

</script>

<template>

  <AppHeader/>

  <!-- <ProjectCard/> -->

  <router-view>

  </router-view>

</template>

<style scoped>

</style>
