<template>
  <app-login msg="Welcome to Your Vue.js App" />
  <app-editor mesaj="naber" />
</template>

<script>
import AppLogin from '../components/Login.vue';
import AppEditor from '../components/Editor.vue';

export default {
  name: 'MainPage',
  components: {
    AppLogin,
    AppEditor,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
