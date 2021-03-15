<template>
  <div>
    <h1>{{ msg }}</h1>
    <input type="text" v-on:keydown.enter.exact="addMessage" />
    <button>Add</button>
  </div>
</template>

<script>
export default {
  name: "Form",
  props: {
    msg: String,
  },
  methods: {
    addMessage(event) {
      
    },
  },
};
</script>
