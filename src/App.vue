<template>
  <v-app>
    <v-navigation-drawer app>
      <app-toolbar />
      <v-divider></v-divider>
      <app-itens-menu />
    </v-navigation-drawer>
    <app-bar />

    <app-carousel/>
    <app-footer/>

  </v-app>
</template>

<script>
import Toolbar from "./components/Toolbar.vue"
import ItensMenu from "./components/ItensMenu.vue";
import AppBar from "./components/AppBar.vue"
import Carousel from "./components/Carousel.vue"
import Footer from "./components/Footer.vue"
export default {
  components: {
    'app-toolbar': Toolbar,
    'app-itens-menu': ItensMenu,
    'app-bar': AppBar,
    'app-carousel': Carousel, 
    'app-footer' : Footer
  },
}
</script>

