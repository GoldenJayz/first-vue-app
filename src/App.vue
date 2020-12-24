<template>
  <div id="app">
    <top />
    <forthewin />
    <test />
    <images />
  </div>
</template>

<script>
import test from './components/test'
import forthewin from './components/forthewin'
import images from './components/images'
import top from './components/top'

export default {
  name: 'App',
  components: {
    test,
    forthewin,
    images,
    top
  }
}
</script>

<style>
body {
  background-color: black;
}
</style>
