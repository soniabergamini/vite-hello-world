<script>
import Hello from './components/Hello.vue';
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';
import Sign from './components/Sign.vue'

export default {
  components: {
    Hello,
    AppTitle,
    AppHero,
    Sign
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
  <footer>
    <Sign />
  </footer>
</template>

<style scoped>

</style>
