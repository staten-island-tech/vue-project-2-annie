<template>
  <body id="body">
    <div>
      <h1 id="maintitle">Beach Please</h1>
      <div id="gallery">
        <div id="titles">
          <!--           <div class="shells">
            <img class="seashell1" src="../images/misc./seashell.PNG" />
            <img class="seashell2" src="../images/misc./seashell.PNG" />
          </div> -->
          <div class="cham">
            <h2 class="names" id="cb">Champagne Beach</h2>
            <div>
              <img
                id="chamimg"
                class="bigpics"
                src="../images/Beaches/champagne beach.jpg" alt ="Champagne Beach"
              />
              <img
                id="chamfood"
                class="foodpics"
                src="../images/Food/Champagne beach food.jpg" alt="Champagne beach food"
              />
            </div>
            <img class="sand" src="../images/Beaches/sand.jpg" alt="Image of sand"/>
          </div>
          <h2 class="activities">Activities</h2>
          <div>
            <img class="actpics" src="../images/Activities/Beach zumba.jpg" alt="Beach zumba"/>
            <h3 class="actdesc">Beach Zumba</h3>
            <img class="actpics" src="../images/Activities/Sand art.jpg" alt="Sand art"/>
            <h3 class="actdesc">Sand Art</h3>
            <img class="actpics" src="../images/Activities/Frisbee.jpg" alt="Frisbee"/>
            <h3 class="actdesc">Frisbee</h3>
          </div>
          <h2 class="reviews">Reviews</h2>
        </div>
        <div class="ora" id="ob">
          <h2 class="names">Ora Beach</h2>
          <div>
            <img id="sand2" class="sand" src="https://bit.ly/3NhBo1R" alt="sand"/>
            <img
              class="bigpics"
              id="oraimg"
              src="../images/Beaches/ora beach.jpg"
              alt="Ora Beach"
            />
            <h2 id="act2" class="activities">Activities</h2>
            <div id="oraacts">
              <img class="actpics2" src="../images/Activities/Water Polo.jpg" alt="Water Polo"/>
              <img
                class="actpics2"
                src="../images/Activities/Jewelry Making.jpg"
                alt="Jewelry Making"
              />
              <img
                class="actpics2"
                src="../images/Activities/Castle construction.jpg"
                alt="Castle Construction"
              />
            </div>
          </div>
          <img
            class="foodpics"
            id="orafood"
            src="../images/Food/Ora beach food.jpg"
            alt="Ora beach food"
          />
          <h2 class="reviews">Reviews</h2>
        </div>
        <div class="stars">
          <h2 class="names" id="sos">Sea of Stars</h2>
          <img class="bigpics" src="../images/Beaches/maldives.jpg" alt="Maldive beach"/>
          <img class="sand" src="../images/Beaches/sand.jpg" alt="Sand"/>
          <h2 class="activities">Activities</h2>
          <div>
            <img
              class="actpics"
              src="../images/Activities/Beach Bonfires.jpg"
              alt="Image of beach bonfire"
            />
            <h3 class="actdesc">Beach Bonfires</h3>
            <img
              class="actpics"
              src="../images/Activities/Sea star gazing.jpg" alt="Image of sea star gazing"
            />
            <h3 class="actdesc">Sea Star Gazing</h3>
            <img class="actpics" src="../images/Activities/Fishing.jpg" alt="Image of fishing"/>
          </div>
          <h2 class="reviews">Reviews</h2>
          <img class="foodpics" src="../images/Food/Sea of Stars food.jpg" alt="Image of sea of stars food"/>
        </div>
        <h3 class=""></h3>
        <div class="copa">
          <h2 class="names" id="c">Copacabana</h2>
          <img class="bigpics" src="../images/Beaches/copacabana.jpg" alt="Image of copacabana beach"/>
          <img class="sand" src="../images/Beaches/sand.jpg" alt="Image of sand"/>
          <h2 class="activities">Activities</h2>
          <div>
            <img class="actpics" src="../images/Activities/Beach volleyball.jpg" alt="Beach volleyball"/>
            <h3 class="actdesc">Beach Volleyball</h3>
            <img class="actpics" src="../images/Activities/Snorkling.jpg" alt="Image of snorkling"/>
            <h3 class="actdesc">Snorkling</h3>
            <img class="actpics" src="../images/Activities/Surfing.jpg" alt="Image of surfing"/>
            <h3 class="actdesc">Surfing</h3>
          </div>
          <h2 class="reviews">Reviews</h2>
          <img class="foodpics" src="../images/Food/Copacabana food.jpg" />
        </div>
        <div class="rena">
          <h2 class="names" id="ri">Renaissance Island</h2>
          <img class="sand" src="../images/Beaches/sand.jpg" />
          <h2 class="activities">Activities</h2>
          <div>
            <img
              class="actpics"
              src="../images/Activities/Flamingo Watching.jpg"
            />
            <h3 class="actdesc">Flamingo Watching</h3>
            <img class="actpics" src="../images/Activities/Jeep Safari.jpg" />
            <h3 class="actdesc">Jeep Safari</h3>
            <img class="actpics" src="../images/Activities/Beach Reading.jpg" />
            <h3 class="actdesc">Beach Reading</h3>
          </div>
          <img
            id="rifood"
            class="foodpics"
            src="../images/Food/Renaissance Island food.jpg"
          />
          <img id="riimg" class="bigpics" src="../images/Beaches/ri.png" />
          <h2 class="reviews">Reviews</h2>
        </div>
        <div>
          <img class="" src="../images/Revs/Info.jpg" />
        </div>
      </div>
    </div>
  </body>
</template>

<script>
import gsap from "gsap";

export default {
  name: "IndexPage",
  mounted: function () {
    this.startAnimations();
  },
  methods: {
    startAnimations: function () {
      const tl = gsap.timeline({ delay: 0.5 });
      gsap.to("#maintitle", { duration: 1, color: "white" });
      tl.from("#gallery", { opacity: 0, duration: 3 });
    },
  },
};
</script>

<style>
@import "style.css";
</style>