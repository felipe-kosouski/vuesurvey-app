<template>
  <div id="app">
    <v-app>
      <app-header app></app-header>
      <v-content>
        <v-container fluid>
          <app-content></app-content>
        </v-container>
      </v-content>
      <app-footer app></app-footer>
    </v-app>
  </div>
</template>

<script>
import appHeader from './components/layout/Header.vue'
import appFooter from './components/layout/Footer.vue'
import appContent from './components/layout/Content.vue'

export default {
  name: 'app',
  components: {
    appHeader,
    appFooter,
    appContent
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
