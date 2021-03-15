<template>
  <div id="app">
    <NavBar></NavBar>
    <div class="container topo">
    <router-view></router-view>
    </div>
  </div>
</template>

<script>
import 'bootstrap/dist/css/bootstrap.css';
import 'bootstrap/dist/js/bootstrap';
import 'font-awesome/css/font-awesome.css';

import NavBar from './components/NavBar';

export default {
  name: 'App',
  components: {
    NavBar
   
  }
}
</script>
<style>
  .topo {
    margin-top:5em;
  }

</style>

