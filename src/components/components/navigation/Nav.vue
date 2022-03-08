<template>
  <nav>
    <v-app-bar app flat color="#F8F8FB">
      <v-app-bar-nav-icon @click="toggleSidenav"></v-app-bar-nav-icon>
      <v-toolbar-title>TrustPaddi Admin</v-toolbar-title>
      <v-spacer />
      <v-badge color="red" dot overlap>
        <v-icon>mdi-bell-outline</v-icon>
      </v-badge>
    </v-app-bar>
  </nav>
</template>

<script>
import { mapMutations } from "vuex";
export default {
  // props:{
  //   toggleSidebar: Function
  // }
  methods: {
    ...mapMutations(["toggleSidenav"]),
  },
};
</script>
