<template>
  <div id="app">
    <img width="25%" :src="avatar" /> {{ message }}
    <button @click="sayHello">click me</button>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";

export default {
  name: "App",
  data() {
    return {
      message:
        " this is super duper fun working with vue.....codebox,github, and netlify is a great workflow choice",
      avatar: "http://placekitten.com/g/300/300"
    };
  },
  methods: {
    sayHello() {
      alert("Vue.js is crazy fun");
    }
  }
};
</script>

<style>
#app {
  font-family: Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: pink;
  background-color: grey;
  margin-top: 60px;
}
</style>
