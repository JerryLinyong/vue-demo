<template>
  <div id="app">
    <demo></demo>
  </div>
</template>

<script>
import demo from './components/demo'
export default {
  name: 'app',
  components: {
    demo: demo
  },
  data () {
    return {
    }
  }
}
</script>

<style>
  body {
    margin: 0
  }
</style>
