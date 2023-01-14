<template>
    <!-- <div class="row m-4">
        <div class="testimonials" >
            
            <div class="card" style="width: 18rem;">
                <img class="card-img-top" :src="image" alt="Card image cap">
                <div class="card-body">
                    
                    <h5 class="card-title">{{ person }} </h5>
                    <p class="card-text">{{ words }} </p>
                    <a href="#" class="btn btn-primary">Go somewhere</a>
                </div>
            </div>
        </div>
    </div> -->
        <div id="carouselExampleIndicators"
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
            <div class="carousel-inner">
              <div class="carousel-item active">
                <div class="card" style="width: 18rem">
                    <img class="card-img-top" :src="image" alt="Card image cap">
                  <div class="card-body">
                    <h5 class="card-title bg-info">{{ person }} </h5>
                    <p class="card-text text-dark">
                        {{ words }} 
                    </p>
                  </div>
                </div>
              </div>
              </div>
              
        </div>
</template>
<script>
   export default {
    name: 'testimonials',
    props: ['id', 'image', 'person', 'words']
}
</script>
<style>
.testimonials {
    display: flex;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
    margin: auto;
}
.grid-box>* {
    margin: auto;
}
.card {
    width: 100%;
    box-shadow: 0px 0px  6px 4px white;
    /* grid-column: span 1; */
}
.card h5 {
    text-align: center; 
}
.card-img-top {
    width: 100%;
    margin: auto;
}
.card-img-top {
   width: 200px !important;
}
.card-text{
    color: black;
}

</style>