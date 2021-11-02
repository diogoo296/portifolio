<template>
  <v-app>
    <AppBar/>

    <v-main>
      <HelloWorld/>
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import AppBar from './components/AppBar'

export default {
  name: 'App',

  components: {
    AppBar,
    HelloWorld,
  },

  data: () => ({
    //
  }),
}
</script>
