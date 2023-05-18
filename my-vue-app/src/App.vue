<script>
import Hello from './components/Hello.vue';
import AppTitle from './components/AppTitle.vue'

export default {
  components: {
    Hello,
    AppTitle
  }
}

</script>

<template>
  <header>
    <Hello />
    <AppTitle />
  </header>
</template>

<style scoped>

</style>
