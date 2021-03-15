<template>
  <div>
    <img alt="Vue logo" src="./assets/logo.png" />
    <Input msg="Todo List" />
  </div>
</template>

<script>
import Input from "./components/Input.vue";
import List from "./components/List.vue";
export default {
  name: "App",
  components: {
    Input,
    List
  },
};
</script>
