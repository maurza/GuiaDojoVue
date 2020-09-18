<template>
   <v-app>
    <Toolbar />
    <v-main>
      <Search />
      <ImageList/>
    </v-main>
  </v-app>
</template>

<script>
import Toolbar from "./components/Toolbar";
import Search from "./components/Search";
import ImageList from "./components/ImageList";


export default {
  name: 'App',

  components: {
    Toolbar,
    Search,
    ImageList
  },

  data: () => ({
    //
  }),
};
</script>
