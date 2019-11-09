<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <User/>
    <Curso/>
  </div>
</template>

<script>
import User from './components/User';
import Curso from './components/Curso';

export default {
  name: 'app',
  components: {
  User,
  Curso  
  }
}
</script>

<style>

</style>
