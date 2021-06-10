<template>
  <div>
  <v-app>
    <v-container fill-height fluid>
      <v-row justify="center" align="center">
        <vue-typed-js :strings="['Work in progress...','Stay tuned ;)']">
        <h1 class="typing"></h1>
        </vue-typed-js>
      </v-row>
    </v-container>
  </v-app>
</div>
</template>

<script>
import Vue from 'vue'
import VueTypedJs from 'vue-typed-js'
Vue.use(VueTypedJs)

export default {
  components: {
  }
}
</script>
