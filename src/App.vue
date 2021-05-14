<template>
  <v-app>
    <Header />
    <v-main>
      <ToDo />
    </v-main>
  </v-app>
</template>

<script>
import Header from "./components/Header";
import ToDo from "./components/ToDo";
export default {
  name: "App",
  components: {
    Header,
    ToDo,
  },
  data: () => ({
    //
  }),
};
</script>
