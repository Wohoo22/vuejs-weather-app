<template>
  <div id='App'>
    <div class="home-container">
      <Home class="home"/>
    </div>
  </div>
</template>

<script>
import Home from './components/Home'
export default {
  name: 'App',
  components: {
    Home
  }
}
</script>

<style>
.home-container .home {
  width: 450px;
}

.home-container {
  margin-left: 500px;
}

body {
  background-color: black;
  margin:0 auto;
}

</style>