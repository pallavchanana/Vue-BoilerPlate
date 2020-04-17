<template>
  <v-app>
 <v-app-bar
      app
      color="primary"
      dark
    >
      <div class="d-flex align-center">
        <v-icon large>mdi-lumx</v-icon>
        <span class="mr-2 title">Vue Boiler Plate</span>
      </div>

      <v-spacer></v-spacer>
        <v-icon>mdi-logout</v-icon>
    </v-app-bar>
      <v-content class="text-center">
      <v-container fluid>
        <transition name="fade" mode="out-in">
          <router-view />
         </transition>
      </v-container>
    </v-content>
  </v-app>
</template>

<script>
export default {
  name: 'App',
};
</script>

<script>

export default {
  name: 'App',
  data: () => ({
    //
  }),
};
</script>
