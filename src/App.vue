<template>
  <div id="app">
    <HeaderMenu />
    <b-container>
      <SearchPage />
    </b-container>
  </div>
</template>

<script>
import HeaderMenu from "./components/HeaderMenu.vue";
import SearchPage from "./components/Search.vue";

export default {
  name: "App",
  components: {
    HeaderMenu,
    SearchPage,
  },
};
</script>

<style></style>
