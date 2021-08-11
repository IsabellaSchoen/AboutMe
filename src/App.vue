/* the output */
<template>
  <div>
    <div class="container">
      <h1>Hello and welcome to AboutMe</h1>

      <b-dropdown no-caret> <!-- no-caret for not showing the dropdown sign-->
        <template #button-content>
          <b-icon icon="list"></b-icon> Menu
        </template>
        <!-- für den Abstand zwischen den Varianten
        <b-dropdown-divider></b-dropdown-divider>
        -->
        <b-dropdown-item>
          <b-icon icon="person-fill"></b-icon>
          AboutMe
        </b-dropdown-item>

        <b-dropdown-item href="https://github.com/IsabellaSchoen">
          <b-icon icon="file-earmark"></b-icon>
          Projects
        </b-dropdown-item>

        <b-dropdown-item>
          <b-icon icon="envelope"></b-icon>
          Contact
        </b-dropdown-item>

      </b-dropdown>

    </div>
  </div>
</template>


/* the logic: the javascript */
<script>
//import menu from './components/Sidebar.vue'

export default {
  name: 'App'
}
</script>


/* the styling */
<style>
.container{
  background-color: lavender;
}

#app {
  font-family: Avenir, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
