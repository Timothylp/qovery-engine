<template>
  <div id="app">
    <QeHero />
  </div>
</template>

<script>
import QeHero from './components/QeHero.vue'

export default {
  name: 'App',
  components: {
    QeHero
  }
}
</script>

<style lang="scss">
@import 'assets/styles/style.scss';
</style>
