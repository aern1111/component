<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png" /> -->
    <Menu  />
  </div>
</template>

<script>
// @ is an alias to /src
import Menu from "@/components/menu.vue";

export default {
  name: "Home",
  components: {
    Menu
  }
};
</script>
