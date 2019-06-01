<template>
  <v-app>
    <v-toolbar color="primary" dark app>
      <v-toolbar-title class="headline">
        <v-layout align-center>
          <i class="material-icons">
          local_dining
          </i>
          <span class="title">Cooky</span>
        </v-layout>
      </v-toolbar-title>
      <v-spacer></v-spacer>
    </v-toolbar>

    <v-content>
      <router-view/>
    </v-content>
  </v-app>
</template>

<script>

export default {
  name: 'App',
  components: {
  },
  data() {
    return {
      //
    };
  },
};
</script>

<style>
  .title {
    padding-left: .5em;
  }
</style>