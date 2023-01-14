<template>
     <div class="contact">
    
 
      <h1 class="ml1">
        <span class="text-wrapper">
          <span class="line line1"></span>
          <span class="letters">CONTACT</span>
          <span class="line line2"></span>
        </span>
      </h1><br>
    </div>
        <br><h4>Email</h4>
        <i class="fa-regular fa-phone-office" loading="lazy"></i>
        <form action="https://formspree.io/f/mdojzboj" method="POST" loading="lazy">
            <div>
                <label for="#firstname">Name</label><br>
                <input id="firstname" name="firstName" type="text" placeholder="Enter your name" required>
            </div>
            <br>
            <div>
                <label for="#surname">Surname</label><br>
                <input id="surname" name="surname" type="text" placeholder="Enter your surname" required>
            </div>
            <br>
            <div>
                <label for="#email">Email</label><br>
                <input id="email" name="email" type="text" placeholder="Enter your email" required>
            </div>
            <br>
            <div>
                <label for="#message">Message</label><br>
                <textarea name="message" cols="30" rows="10"></textarea>
            </div>
           
            <div>
                <input type="submit" value="submit" class="btn btn-primary mb-4">
            </div>
        </form>
        <br><h4>Contacts</h4>
        <ul class="numbers">
            <li><b>071 415 9013</b></li>|
            <li><b>063 723 8514</b></li>|
            <li><b>082 862 7744</b></li>
        </ul>
    <!-- </form> -->
</template>
<style>
.numbers {
    list-style: none;
    display: inline-flex;
    gap: 30px;
    font-size: large;
    background-color: black;
}
</style>