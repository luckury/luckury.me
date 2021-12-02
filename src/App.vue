<template>
  <Hello />
  <Links />
</template>

<script>
import Hello from './components/Hello.vue'
import Links from './components/Links.vue'

export default {
  name: 'App',
  components: {
    Hello,
    Links
  }
}
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Bitter:wght@300&display=swap');

html {
  overflow: scroll;
}

::-webkit-scrollbar {
    width: 0px;
    background: transparent; /* make scrollbar transparent */
}

body {
  margin: 0;
}

#app {
  font-family: 'Bitter', serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
