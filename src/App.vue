<template>
  <div class="corpo">
    <navbar></navbar>
  </div>
</template>

<script>

import Navbar from "./components/navbar.vue";
import { routes } from "./routes";


export default {
  components: {
    Navbar
  },

  data() {
    return {
      routes
    };
  }
};
</script>

<style scoped>

</style>
