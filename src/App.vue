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

        <a href="" target="_blank">
          <b-button variant="outline-dark">
            <b-icon icon="envelope"></b-icon>
            Contact
          </b-button>
        </a>


        <b-button variant="outline-dark">
          <b-icon icon="tools"></b-icon>
          Feedback
        </b-button>
      </b-button-group>

    </nav>


    <div class="person">
      <h2>
        Who am I?
      </h2>
      <div class="">
        <p>
          My name is Isabella Schön.
          I am a student at the HTWG in Konstanz.
          My focus in my study Applied Computer Science is the Hardware and Software of the computer.
          But my main focus is Embedded Systems. Here we explore the different dependencies of the technique
          and how each can be affected by changing sometimes just a single line.
        </p>
      </div>
    </div>


    <div class="project">
      <h2>
        Projects I participated.
      </h2>



      <b-container class="">
        <b-row>
          <b-col>
            <a href="https://github.com/IsabellaSchoen/WizardChess" target="_blank">
              <img src="./assets/wizard.png"  width="300" height="200">
            </a>
          </b-col>
          <b-col>
            <a href="https://github.com/IsabellaSchoen/resy-ss21-assignments-grp1" target="_blank">
              <img src="./assets/realzeitsysteme.png" width="350" height="200">
            </a>
          </b-col>
          <b-col>
            <a href="https://github.com/IsabellaSchoen/pir-ss21-grp4" target="_blank">
              <img src="./assets/rust.png" width="350" height="200">
            </a>
          </b-col>
        </b-row>
      </b-container>


    </div>


    <div class="free-project">

      <div class="">
        <h2>
          Free-time projects.
        </h2>
      </div>

      <div class="card-img-top d-flex align-items-center bg-floralwhite">

        <div>
          <b-carousel
              id="carousel-fade"
              style="text-shadow: 0px 0px 2px #000"
              fade
              indicators
              img-width="1024"
              img-height="480"
          >
            <b-carousel-slide
                img-src="https://picsum.photos/1024/480/?image=55"
            ></b-carousel-slide>
            <b-carousel-slide
                img-src="https://picsum.photos/1024/480/?image=54"
            ></b-carousel-slide>
            <b-carousel-slide
                img-src="https://picsum.photos/1024/480/?image=53"
            ></b-carousel-slide>
          </b-carousel>
        </div>

        <p class="col p-2 m-0">In my free-time I enjoy painting with acryl colours.
          With painting I have the possibilities to express my inner feelings or
          to reproduce impressions in my own imagination.
        </p>

      </div>

    </div>


    <div class="inspi">
      <h2 style="color: black">
        Inspirations.
      </h2>

      <div>
        <b-link href="https://en.wikipedia.org/wiki/Edward_Snowden">Edward Snowdengit </b-link>
      </div>

      <div>
        <b-link href="https://www.w3schools.com/">w3schools</b-link>
      </div>

      <div>
        <b-link href="https://exercism.io/">Exercism</b-link>
      </div>

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
