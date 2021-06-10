<template>
  <v-app dark>
    <v-main>
      <v-container>
        <nuxt />
      </v-container>
    </v-main>

    <v-footer
      :absolute="!fixed"
      app
    >
    </v-footer>
  </v-app>
</template>

<script>
export default {
}
</script>
