<template>
  <v-app id="app">
    <app-navigation></app-navigation>
  </v-app>
</template>

<script>
    import AppNavigation from '@/components/AppNavigation';
export default {
  name: 'App',
  components: {
    AppNavigation
  }
}
</script>
