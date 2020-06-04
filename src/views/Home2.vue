<template>
  <div class="home">
    <!-- Masthead-->
    <header class="masthead">
      <div style="background: rgba(255, 255, 255, 0.1);">
        <div class="masthead-heading">
          Cup of Codes
        </div>

        <img
          alt="Vue logo"
          src="../assets/newCup3.png"
          style="width: 20%; height:20%;margin-top: 5px; margin-bottom: 5px;"
        />
        <!-- <div class="masthead-heading text-uppercase">It's Nice To Meet You</div> -->
        <HelloWorld></HelloWorld>
      </div>
    </header>
    <!-- Portfolio-->
    <div id="portfolio">
      <div class="container-fluid p-0">
        <div class="row no-gutters">
          <div class="col-lg-4 col-sm-6">
            <a class="portfolio-box" href="../assets/fullsize/1.jpg"
              ><img class="img-fluid" src="../assets/thumbnails/1.jpg" alt="" />
              <div class="portfolio-box-caption">
                <div class="project-category text-white-50">Category</div>
                <div class="project-name">Project Name</div>
              </div></a
            >
          </div>
          <div class="col-lg-4 col-sm-6">
            <a class="portfolio-box" href="../assets/fullsize/2.jpg"
              ><img class="img-fluid" src="../assets/thumbnails/2.jpg" alt="" />
              <div class="portfolio-box-caption">
                <div class="project-category text-white-50">Category</div>
                <div class="project-name">Project Name</div>
              </div></a
            >
          </div>
          <div class="col-lg-4 col-sm-6">
            <a class="portfolio-box" href="../assets/fullsize/3.jpg"
              ><img class="img-fluid" src="../assets/thumbnails/3.jpg" alt="" />
              <div class="portfolio-box-caption">
                <div class="project-category text-white-50">Category</div>
                <div class="project-name">Project Name</div>
              </div></a
            >
          </div>
          <div class="col-lg-4 col-sm-6">
            <a class="portfolio-box" href="../assets/fullsize/4.jpg"
              ><img class="img-fluid" src="../assets/thumbnails/4.jpg" alt="" />
              <div class="portfolio-box-caption">
                <div class="project-category text-white-50">Category</div>
                <div class="project-name">Project Name</div>
              </div></a
            >
          </div>
          <div class="col-lg-4 col-sm-6">
            <a class="portfolio-box" href="../assets/fullsize/5.jpg"
              ><img class="img-fluid" src="../assets/thumbnails/5.jpg" alt="" />
              <div class="portfolio-box-caption">
                <div class="project-category text-white-50">Category</div>
                <div class="project-name">Project Name</div>
              </div></a
            >
          </div>
          <div class="col-lg-4 col-sm-6">
            <a class="portfolio-box" href="..?assets/fullsize/6.jpg"
              ><img class="img-fluid" src="../assets/thumbnails/6.jpg" alt="" />
              <div class="portfolio-box-caption p-3">
                <div class="project-category text-white-50">Category</div>
                <div class="project-name">Project Name</div>
              </div></a
            >
          </div>
        </div>
      </div>
    </div>
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
