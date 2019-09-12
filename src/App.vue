<template>
  <div id="app">
    <Header></Header>
    <div class="tab">
      <router-link to='/goods'>goods</router-link>
      <router-link to='/ratings'>ratings</router-link>
      <router-link to='/seller'>seller</router-link>
    </div>
    <router-view/>
  </div>
</template>

<script>
import Header from './components/header/header.vue'
export default {
  name: 'App',
  components: {
    Header
  }
}
</script>

<style>

</style>
