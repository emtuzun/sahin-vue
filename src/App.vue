<template>
  <app-admin />
  <app-main-page />
</template>

<script>
import AppAdmin from './views/Admin.vue';
import AppMainPage from './views/MainPage.vue';

export default {
  name: 'App',
  components: {
    AppAdmin,
    AppMainPage,
  },
};
</script>

<style></style>
