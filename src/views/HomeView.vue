<template>
        <div>
          <div
            id="carouselExampleControls0"
            class="carousel slide landing-carousel"
            data-bs-ride="carousel"
            data-aos="zoom-in"
          >
            <div class="carousel-inner">
              <div class="carousel-item active" data-bs-interval="4500">
                <img
                  src="https://i.postimg.cc/1z7mnBJP/DSC-3541.jpg"
                  class="d-block w-100"
                  alt="..."
                  loading="lazy"
                />
                <h3 class="hd1">Hi, My name Is Tyvon</h3>
              </div>
              <div class="carousel-item" data-bs-interval="5000">
                <img
                  src="https://i.postimg.cc/d3fwHjhv/Screenshot-2022-11-05-101911.png"
                  class="d-block w-100"
                  alt="..."
                  loading="lazy"
                />
                <h3 class="hd1"><b>I'm an aspiring web-developer</b></h3>
              </div>
              <div class="carousel-item" data-bs-interval="4500">
                <img
                  src="https://i.postimg.cc/qvxM0nYc/Screenshot-2022-11-05-103247.png"
                  class="d-block w-100"
                  alt="..."
                  loading="lazy"
                />
                <h3 class="hd1">This is my Web-site, Enjoy!</h3>
              </div>
            </div>
            <button
              class="carousel-control-prev"
              type="button"
              data-bs-target="#carouselExampleControls0"
              data-bs-slide="prev"
            >
              <span
                class="carousel-control-prev-icon"
                aria-hidden="true"
              ></span>
              <span class="visually-hidden">Previous</span>
            </button>
            <button
              class="carousel-control-next"
              type="button"
              data-bs-target="#carouselExampleControls0"
              data-bs-slide="next"
            >
              <span
                class="carousel-control-next-icon"
                aria-hidden="true"
              ></span>
              <span class="visually-hidden">Next</span>
            </button>
          </div>
        </div>
        <br />
        <p class="para" data-aos="fade-right">
          Having a website is an opportunity to make a great first impression
          and give people comfort that you're a real business. Showcasing your
          brand to your prospective customers is one of the most important
          things that you can do.
        </p>
          
          <div
            id="carouselExampleIndicators"
            class="carousel slide"
            data-bs-ride="true"
          >
            <div class="carousel-indicators d-none">
              <button
                type="button"
                data-bs-target="#carouselExampleIndicators"
                data-bs-slide-to="0"
                class="active"
                aria-current="true"
                aria-label="Slide 1"
              ></button>
              <button
                type="button"
                data-bs-target="#carouselExampleIndicators"
                data-bs-slide-to="1"
                aria-label="Slide 2"
              ></button>
              <button
                type="button"
                data-bs-target="#carouselExampleIndicators"
                data-bs-slide-to="2"
                aria-label="Slide 3"
              ></button>
              <button
                type="button"
                data-bs-target="#carouselExampleIndicators"
                data-bs-slide-to="3"
                aria-label="Slide 4"
              ></button>
              <button
                type="button"
                data-bs-target="#carouselExampleIndicators"
                data-bs-slide-to="4"
                aria-label="Slide 5"
              ></button>
              <button
                type="button"
                data-bs-target="#carouselExampleIndicators"
                data-bs-slide-to="5"
                aria-label="Slide 6"
              ></button>
            </div>
    
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>






















 