<template>
  <main>
    <v-app>
      <v-content>
        <guest-navigations></guest-navigations>
        <v-container class="my-5">
          <router-view/>
        </v-container>
      </v-content>
    </v-app>
  </main>
</template>

<script>
  import GuestNavigations from '@/navigations/guest';
  export default {
    name: 'App',
    components: {
      GuestNavigations
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
  margin-top: 60px;
}
</style>
