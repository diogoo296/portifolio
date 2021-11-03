<template>
  <v-container>
    <v-row>
      <v-col class="mb-12">
        <v-card>
          <v-container>
            <v-row>
              <v-col cols="3">
                <v-avatar size="250">
                  <img :src="require('../assets/avatar.jpg')" alt="Avatar">
                </v-avatar>
              </v-col>
              <!-- <v-divider vertical></v-divider> -->
              <v-col cols="3" align-self="center">
                <h1>Diogo M. Santana</h1>
                <div class="text-overline">Technical Team Lead</div>
                <div class="text-overline">Full-Stack Developer</div>
              </v-col>
              <v-divider vertical></v-divider>
              <v-col cols="6" class="text-justify" align-self="center">
                I'm a Full-Stack developer with 5 years of experience in Web Development. Furthermore, I also have about 1 year of
                experience managing small teams and leading projects.
              </v-col>
            </v-row>
          </v-container>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
  export default {
    name: 'About',

    data: () => ({
    }),
  }
</script>
