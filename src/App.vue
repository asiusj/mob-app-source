<template>
  <v-app>
    <v-content>
      <router-view></router-view>
      <!-- <GreetingsPage /> -->
    </v-content>
  </v-app>
  
</template>

<script lang="ts">
import Vue from "vue";


export default Vue.extend({
  name: "App",
});
</script>

<style lang="scss" scoped>
// .v-content {
//   background-image: url("./assets/woman.svg");
// }
</style>
