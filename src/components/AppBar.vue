<template>
  <v-app-bar
    app
    color="primary"
    dark
  >
    <v-tabs>
      <v-tab>Home</v-tab>
      <v-tab>About</v-tab>
      <v-tab>Skills</v-tab>
      <v-tab>Experience</v-tab>
      <v-tab>Contact</v-tab>
    </v-tabs>
  </v-app-bar>
</template>

<script>
  export default {
    name: 'AppBar',

    data: () => ({
    }),
  }
</script>
