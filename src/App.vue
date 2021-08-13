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

      <div class="aC4gN7">
        <h2 style="color: black">
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
  background-color: floralwhite !important;
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

.container{
  background-color: floralwhite;
}

.card-img-top {

}

.person{
  text-align: left;
}

.free-project{
  text-align: left;
}

.project{
  text-align: left;
}

.inspi{
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
