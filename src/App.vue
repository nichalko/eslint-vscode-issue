<template>
  <div id="app">
    <img
      alt="Vue logo"
      src="./assets/logo.png"
    >
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

const myLongVariableName = "some string here";

function myFunctionWithWrongIndentation(myLongVariableName) {
  if (myLongVariableName === "b") {
  console.log("wrong indentation is here");
  
  
  
            console.log("so is here");


    console.log("and extra space");
  }
}

myFunctionWithWrongIndentation();

export default {
  name: "App",
  components: {
// wrong indentation
HelloWorld
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
