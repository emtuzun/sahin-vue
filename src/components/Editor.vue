<template>
  <h1>{{ mesaj }}</h1>
</template>

<script>
export default {
  name: 'Editor',
  props: {
    mesaj: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
