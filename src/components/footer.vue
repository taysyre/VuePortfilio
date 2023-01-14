<template>
    <footer>
          <a href="https://en-gb.facebook.com/tyvon.april.12/" class="fa fa-facebook"></a>
          <a href="https://twitter.com/TayApril1" class="fa fa-twitter"></a>
          <a href="https://www.instagram.com/tyvonapril077/" class="fa fa-instagram"></a><br />
          <br />
          <p>Copyright &copy; 2023</p>
        </footer>
</template>
<script>

export default {
  name: 'footerComp'
}

</script>
<style>
/* footer */
footer p {
    font-weight: bold;
}


.fa {
    padding: 20px;
    font-size: 20px;
    width: 50px;
    align-items: center;
    text-decoration: none;
    margin: 5px 5px;

  }
  
  .fa:hover {
      opacity: 0.7;
      color: aqua;
  }
 /* Facebook */
.fa-facebook {
    background: #1b51c6;
    color: white;
    align-items: center;
  }
  
  /* Twitter */
  .fa-twitter {
    background: #55ACEE;
    color: white;
    align-items: center;
  }
  .fa-instagram {
    background: #ffa202;
    color: white;
    align-items: center;
  }

footer {
    color: #fff;
    text-align: center;
    z-index: 10;
    position: relative;
    top: 150px;
}

</style>