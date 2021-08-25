/* the output */
<template>
  <div class="main-content">
    <nav class="container">
      <h1>
        Hello and welcome to AboutMe!
      </h1>

      <b-button-group class="button-group">

        <a href="https://www.linkedin.com/in/isabella-sch%C3%B6n-854311211/" target="_blank">
          <b-button variant="outline-dark">
            <b-icon icon="person-fill"></b-icon>
            AboutMe
          </b-button>
        </a>

        <a href="https://github.com/IsabellaSchoen" target="_blank">
          <b-button variant="outline-dark">
            <b-icon icon="file-earmark"></b-icon>
            Projects
          </b-button>
        </a>


        <router-link to="/contact">
          <b-button variant="outline-dark">
            <b-icon icon="envelope"></b-icon>
            Contact
          </b-button>
        </router-link>

      </b-button-group>
    </nav>
    <router-view/>
  </div>
</template>


/* the logic: the javascript */
<script>

export default {
  name: 'App'
}
</script>


/* the styling */
<style>

body {
  background-color: floralwhite !important;
}

h1, h2 {
  color: black;
}


p {
  text-indent: 50px;
  text-align: center;
  letter-spacing: 1px;
  text-decoration: none;
  line-height: 1.2;
  word-spacing: 0px;
  background-color: floralwhite;
  color: black;
}

.container {
  background-color: floralwhite;
}

.card-img-top {

}

.person {
  text-align: left;
}

.free-project {
  text-align: left;
}

.project {
  text-align: left;
}

.inspi {
  text-align: left;
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