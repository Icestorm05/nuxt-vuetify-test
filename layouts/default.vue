<template>
  <v-app>
    <v-toolbar app color="primary" fixed>
      <v-toolbar-side-icon class="white--text"></v-toolbar-side-icon>
      <v-toolbar-title>Test</v-toolbar-title>
    </v-toolbar>
  </v-app>
</template>

<script>
import VToolbar, { VToolbarSideIcon, VToolbarTitle } from 'vuetify/es5/components/VToolbar';
export default {
  components: {
    VToolbar,
    VToolbarSideIcon,
    VToolbarTitle,
  },
}
</script>
