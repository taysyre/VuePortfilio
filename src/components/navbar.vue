<template>
    <div class="nav">
        <nav class="navbar navbar-expand-lg navbar-dark">
        <div class="container-fluid" id="box">
          <img
            class="icon"
            src="https://i.postimg.cc/wxRfkgYK/Screenshot-2022-10-07-094215.png"
            alt="logo"
            loading="lazy"
          /><br />

          <button
            class="navbar-toggler ms-5"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <br />
              <ul class="d-flex flex-column flex-sm-row">
                
                  <li><router-link to="/">Home</router-link> </li>
                  <li><router-link to="/about">About</router-link></li>
                  <li> <router-link to="/resume">Resume</router-link></li>
                  <li><router-link to="/projects">Projects</router-link></li>
                  <li><router-link to="/testimonials">Testimonials</router-link></li>
                  <li> <router-link to="/contact">Contact</router-link></li>
               
              </ul>
            </ul>
          </div>
        </div>
      </nav>
    </div>
</template>
<script>

export default {
  name: 'navbar'
}

</script>
<style>
.icon { 
    width: 8em;
    border-radius: 4em;
}
.icon:hover { 
    box-shadow: 0 0 6px 4px rgb(249, 246, 246);
    scale: 1.1;
}
nav ul{
    display: flex;
    justify-content: center;
    align-items: center;
}
nav ul li{
    list-style: none;
    margin-left:  20px;
}
nav ul li a{
    text-decoration: none;
    padding: 6px 15px;
    color: #fff;
    border-radius: 20px;
}
nav ul li a:hover,
nav ul li .router-link-exact-active {

    background: #fff;
    color: #2b1055
}
</style>