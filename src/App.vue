<template>
  <Registration_Form />
</template>

<script>
import Registration_Form from "../src/components/Registration_Form.vue";

export default {
  name: "App",
  components: {
    Registration_Form,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;
  margin-top: 60px;
}
</style>
