<template>
  <div id="app">
    <img src="./assets/logo.png">
    <h1>{{ msg }}</h1>
    <h2>Essential Links</h2>
    <h2>______________________________________</h2>
    
    <!-----Demo 1, Insert the component name, as show below---->
    <about-us></about-us>>
    <h2>______________________________________</h2>
    <todo-cards></todo-cards>

  </div>
</template>

<script>
import AboutUs from './components/AboutUs.vue'
import TodoCards from './components/TodoCard.vue'
//----------------------------------------//
export default {
  components: { AboutUs, TodoCards },
  name: 'app',

  data () {
    return {
      msg: 'The Main Component'
    }
  }
}
//----------------------------------------//



</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
