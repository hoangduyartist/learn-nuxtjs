<template>
  <v-card
    color="grey lighten-4"
    flat
    tile
  >
    <v-toolbar dense class="toolbar">
      <v-app-bar-nav-icon></v-app-bar-nav-icon>

      <v-toolbar-title class="toolbarTittle"><span style="font-weight: 700;">vuetify</span> - nuxtjs</v-toolbar-title>
    <!-- ~ justify space-between -->
      <v-spacer></v-spacer>

      <v-btn icon>
        <v-icon>mdi-magnify</v-icon>
      </v-btn>

      <v-btn icon>
        <NuxtLink to="/login" class="loginLink"><v-icon>mdi-login</v-icon></NuxtLink>
      </v-btn>

      <!-- <v-btn icon>
        <v-icon>mdi-heart</v-icon>
      </v-btn>

      <v-btn icon>
        <v-icon>mdi-dots-vertical</v-icon>
      </v-btn> -->

      <v-btn icon>
        <v-icon>mdi-translate</v-icon>
      </v-btn>
    </v-toolbar>
  </v-card>
</template>
<style scoped>
.toolbar {
  height: fit-content !important;  
  padding: 10px 0 !important;
}
.toolbarTittle {
  text-transform: uppercase;
  color: #41b883;
  letter-spacing: 4px;
  font-size: 22px;
}
.loginLink {
  text-decoration: none;
  color: currentColor;
}
.loginLink:visited, .loginLink:active {
  color: currentColor;
}
/* .loginLink:active {
  color: currentColor;
} */
</style>