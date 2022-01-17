<template>
  <v-app>
    <v-app-bar app>
      <v-container>
        <v-row>
          <v-col class="d-flex ml-16">
            <div class="d-flex align-center">
              <v-img src="./assets/logoup.png" />
              <v-img height="18" class="ml-10" src="./assets/4flags.png" />
            </div>           
          </v-col>
        </v-row>
      </v-container>
    </v-app-bar>
    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: "App",
  data: () => ({
    //
  }),
};
</script>

<style> 
* {
  font-family: Fira Sans, sans-serif;
}

body {
background: #6400AC;
}
</style>