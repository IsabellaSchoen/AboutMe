/* the output */
<template>
  <div class="main-content">

    <nav class="container">
      <h1 style="color: black">
        Hello and welcome to AboutMe
      </h1>

      <b-button-group class="button-group">
        <b-button variant="outline-dark" href="https://www.linkedin.com/in/isabella-sch%C3%B6n-854311211/">
          <b-icon icon="person-fill"></b-icon> AboutMe
        </b-button>
        <b-button variant="outline-dark" href="https://github.com/IsabellaSchoen">
          <b-icon icon="file-earmark"></b-icon> Projects
        </b-button>
        <b-button variant="outline-dark">
          <b-icon icon="envelope"></b-icon> Contact
        </b-button>
        <b-button variant="outline-dark">
          <b-icon icon="tools"></b-icon> Feedback
        </b-button>
      </b-button-group>

    </nav>


    <div class="person">
      <h1 style="color: black">
        Who am I?
      </h1>
    </div>

    <div class="project">
      <h1 style="color: black">
        Projects I participated.
      </h1>
    </div>

    <div class="free-project">
      <h1 style="color: black">
        Free-time projects.
        <div class="card">
          <div class="card-img-top d-flex align-items-center">
            <div>
             <img src="assets/ducks.png"> 
            </div>
            <p class="col p-2 m-0">Here are ducks.</p>
          </div>
        </div>

      </h1>
    </div>

    <div class="inspi">
      <h1 style="color: black">
        Inspirations.
      </h1>
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

body {
  background-color: antiquewhite !important;
}


.container{
  background-color: antiquewhite;
}

.main-content {
  font-family: Avenir, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>




<!--
<nav class="container">
      <h1 style="color: black">
        Hello and welcome to AboutMe
      </h1>

      <b-dropdown no-caret dropright> //no-caret for not showing the dropdown sign
<template #button-content>
  <b-icon icon="list"></b-icon> Menu
</template>

// für den Abstand zwischen den Varianten: <b-dropdown-divider></b-dropdown-divider>

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

</nav>
-->
