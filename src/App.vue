<template>
  <v-app>
    <AppBar/>

    <v-main>
      <About/>
    </v-main>
  </v-app>
</template>

<script>
import About from './components/About'
import AppBar from './components/AppBar'

export default {
  name: 'App',

  components: {
    AppBar,
    About,
  },

  data: () => ({
    //
  }),
}
</script>
