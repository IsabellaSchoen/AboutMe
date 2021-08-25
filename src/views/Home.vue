<template>
  <div class="home">
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
              <img src="@/assets/wizard.png"  width="300" height="200">
            </a>
          </b-col>
          <b-col>
            <a href="https://github.com/IsabellaSchoen/resy-ss21-assignments-grp1" target="_blank">
              <img src="@/assets/realzeitsysteme.png" width="350" height="200">
            </a>
          </b-col>
          <b-col>
            <a href="https://github.com/IsabellaSchoen/pir-ss21-grp4" target="_blank">
              <img src="@/assets/rust.png" width="350" height="200">
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
        <b-link href="https://en.wikipedia.org/wiki/Edward_Snowden" target="_blank">Edward Snowden</b-link>
      </div>

      <div>
        <b-link href="https://www.w3schools.com/" target="_blank">w3schools</b-link>
      </div>

      <div>
        <b-link href="https://exercism.io/" target="_blank">Exercism</b-link>
      </div>

    </div>
  </div>
</template>

<script>

export default {
  name: "Home"
};
</script>