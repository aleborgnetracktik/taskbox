<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import store from "@/store";
import TaskList from "@/components/PureTaskList";

export default {
  name: "App",
  store,
  components: {
    TaskList
  }
};
</script>

<style>
  @import 'index.css';
</style>
