<template>
  <div id="app">
    <div class="urna"></div>
  </div>
</template>

<script>
import '@/css/global.css';

export default {
  name: 'App',
  components: {
  }
}
</script>

<style>
#app {
  background-color: var(--background-color);
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}

.urna{
  width: 100%;  
}
</style>
