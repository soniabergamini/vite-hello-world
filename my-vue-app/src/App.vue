<script>
import Hello from './components/Hello.vue';
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue'

export default {
  components: {
    Hello,
    AppTitle,
    AppHero
  }
}

</script>

<template>
  <main>
    <Hello />
    <AppTitle />
    <section>
      <AppHero />
    </section>
  </main>
</template>

<style scoped>

</style>
