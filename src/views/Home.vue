<template>
  <v-layout class="search-parent" justify-center>
    <v-flex xs12 sm6>
      <v-card class="search-card">
        <v-layout justify-center>
          <v-flex xs12 md6>
            <h5 class="landing-p headline">Cooky is an easier way to search for recipes, simply enter your search criteria and let Cooky do the rest.</h5>
          </v-flex>
        </v-layout>
        <v-layout justify-center>
          <v-flex xs12 md6>
            <v-text-field
            label="Recipe Search"
            single-line
            outline
            class="search-box"
            ></v-text-field>
          </v-flex>
        </v-layout>
        <v-layout justify-center class="search-button">
          <v-btn color="secondary">Cook</v-btn>
        </v-layout>
      </v-card>
    </v-flex>
    
  </v-layout>
</template>

<script>

export default {
  components: {
  },
};
</script>

<style>
  .search-parent {
    padding-top: 10em;
    width: 100%;
    height: 100%;
    background-image: url(../../public/bg.jpg);
    background-repeat: no-repeat;
    background-size: cover;
  }
  .search-box {
    -ms-flex-align: center;
  }
  .search-button {
    padding-bottom: 2em;
  }
  .landing-p {
    text-align: center;
    padding-top: 1em;
    padding-bottom: 1.2em;
  }
  .search-card {
    background-color: rgba(255, 255, 255, .7)!important;
  }
</style>