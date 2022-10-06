<template>
  <h2 class="header-title">Welcome</h2>
  <h5>{{ name }}</h5>
</template>


<script>
export default {
  name: 'App',
  data () {
    return {
      name: "Mr.SoftwareEngineer",
    }
  }
}
</script>


<style>
 * {
   background-color: rgba(70, 130, 180, 0.68);
 }
</style>
