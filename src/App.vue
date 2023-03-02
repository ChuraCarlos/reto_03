<template>
  <div id="app">
    <FrameVoto/>
  </div>
</template>

<script>
import FrameVoto from './components/FrameVoto.vue'

export default {
  name: 'App',
  components: {
    FrameVoto
  }
}
</script>

<style>
html {
  margin: 0 !important;
  padding: 0 !important;
}
body {
  margin: 0 !important;
  padding: 0 !important;
  background-color: #ECF2F7;
}
#app {
  width: 100%;
  height: 100%;
  padding: 0px;
  margin: 0px;
  
}
</style>
