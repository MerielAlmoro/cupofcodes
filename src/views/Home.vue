<template>
  <div class="home">
    <!-- Masthead-->
    <header class="masthead">
      <div class="container">
        <!-- <div class="masthead-subheading">Cup of Codes</div> -->
        <div class="masthead-heading">
          Cup of Codes
        </div>
        <!-- <img
          alt="Vue logo"
          src="../assets/ccp_logo.png"
          style="width: 200px;"
        /> -->
        <!-- <img
          alt="Vue logo"
          src="../assets/newCup2.jpg"
          style="width: 30%; height:30%; margin-top: 5%; margin-bottom: 5%; opacity: 0.8; border-radius: 50%;"
        /> -->
        <img
          alt="Vue logo"
          src="../assets/newCup3.png"
          style="width: 30%; height:30%;margin-top: 5%; margin-bottom: 5%;"
        />
        <!-- <div class="masthead-heading text-uppercase">It's Nice To Meet You</div> -->
        <!-- <HelloWorld msg="Cup of Codes" /> -->
        <HelloWorld></HelloWorld>
      </div>
    </header>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld
  }
};
</script>
