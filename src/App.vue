<template>
  <div id="app" class="container">
    <img src="./assets/logo.png" class="logo" />
    <TodoList></TodoList>
    <router-view />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
import TodoList from "./components/TodoList";

export default {
  name: "App",
  components: {
    HelloWorld,
    TodoList
  }
};
</script>

<style>
* {
  box-sizing: border-box;
}
#app {
  color: #2c3e50;
  margin-top: 60px;
  font-size: 24px;
}
.container {
  max-width: 600px;
  margin: 0 auto;
}
.logo {
  display: block;
  margin: 20px auto;
  height: 75px;
}
</style>
