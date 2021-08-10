<template>
  <div class="Home"> 
      <section class="content">
           <p>
          Google Pay for Passes makes it easy for your customers to save boarding passes, 
          loyalty programs, offers, gift cards, and tickets to their phones for easy access at the right time. 
          It also lets you engage them through location-based notifications, real-time updates, and more.This site is built using VueJS, Node.js, 
        AWS LambdA for hosting APIs.
        </p>
        <p></p>
        <p>Visit the loyalty pages:</p>
        <ul>
          <li>
            <Link to="/sign-up">Loyalty sign-up</Link>
          </li>
          <li>
            <Link to="/sign-in">Loyalty sign-in</Link>
          </li>
          <li>
            <Link to="/rewards">Loyalty rewards</Link>
          </li>
        </ul>


      </section>
  </div>

</template>



<script>
export default {
    name: 'Home',
    props: '',
}
</script>




<style>
.Home{
  text-align: center;
  margin: 20px;
}


.Home .content {
  max-width: 600px;
  margin: 0 auto;
  text-align: left;
  color: white;
}
</style>