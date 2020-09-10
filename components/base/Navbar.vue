<template>
  <v-app-bar app color="primary" flat>
    <v-container class="py-0 fill-height">
      <v-app-bar-nav-icon class="mr-3">
        <v-img
          :src="require('@/assets/logo_nobg.png')"
          height="50"
          width="50"
        ></v-img>
      </v-app-bar-nav-icon>
      <v-toolbar-title class="white--text toolbar-title logo"
        >Muslims Meet Online</v-toolbar-title
      >
      <v-spacer></v-spacer>
      <v-btn icon large>
        <v-badge color="error" dot bordered overlap>
          <v-icon color="white">mdi-bell-outline</v-icon>
        </v-badge>
      </v-btn>
      <v-btn class="ml-1" icon large>
        <v-badge color="error" dot bordered overlap>
          <v-icon color="white">mdi-message-outline</v-icon>
        </v-badge>
      </v-btn>
      <v-btn class="ml-1" icon large>
        <v-icon color="white">mdi-account</v-icon>
      </v-btn>
      <v-btn class="ml-1" icon large>
        <v-icon color="white">mdi-cog-outline</v-icon>
      </v-btn>
      <v-btn class="ml-1" icon large>
        <v-icon color="warning">mdi-exit-to-app</v-icon>
      </v-btn>
    </v-container>
  </v-app-bar>
</template>

<style scoped>
.logo {
  font-size: 27px !important;
}
</style>
