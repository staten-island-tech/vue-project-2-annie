<template>
  <body id="body">
    <div>
      <h1 id="maintitle">Beach Please</h1>
      <div id="gallery">
        <div id="titles">
          <div class="cham">
            <h2 class="names" id="cb">Champagne Beach</h2>
            <div>
              <img
                id="chamimg"
                class="bigpics"
                src="../images/Beaches/champagne beach.jpg"
              />
              <img
                id="chamfood"
                class="foodpics"
                src="../images/Food/Champagne beach food.jpg"
              />
            </div>
            <img class="sand" src="../images/Beaches/sand.jpg" />
            <h2 class="activities">Activities</h2>
            <div>
              <img class="actpics" src="../images/Activities/Beach zumba.jpg" />
              <img class="actpics" src="../images/Activities/Sand art.jpg" />
              <img class="actpics" src="../images/Activities/Frisbee.jpg" />
            </div>
            <h2 class="reviews">Reviews</h2>
            <img src="../images/Revs/Cham Rev 1.jpg" alt="" />
            <img src="../images/Revs/Cham Rev 2.jpg" alt="" />
            <img src="../images/Revs/Cham Rev 3.jpg" alt="" />
            <img src="../images/Revs/Cham Rev 4.jpg" alt="" />
          </div>
          <div class="ora" id="ob">
            <h2 id="obname" class="names">Ora Beach</h2>
            <div>
              <img id="sand2" class="sand" src="https://bit.ly/3NhBo1R" />
              <img
                class="bigpics"
                id="oraimg"
                src="../images/Beaches/ora beach.jpg"
              />
              <h2 id="act2" class="activities">Activities</h2>
              <div id="oraacts">
                <img
                  class="actpics2"
                  src="../images/Activities/Water Polo.jpg"
                />
                <img
                  class="actpics2"
                  src="../images/Activities/Jewelry Making.jpg"
                />
                <img
                  class="actpics2"
                  src="../images/Activities/Castle construction.jpg"
                />
              </div>
            </div>
            <img
              class="foodpics"
              id="orafood"
              src="../images/Food/Ora beach food.jpg"
            />
            <h2 class="reviews">Reviews</h2>
            <img src="../images/Revs/Ora Rev 1.jpg" alt="" />
            <img src="../images/Revs/Ora Rev 2.jpg" alt="" />
            <img src="../images/Revs/Ora Rev 3.jpg" alt="" />
            <img src="../images/Revs/Ora Rev 4.jpg" alt="" />
          </div>
          <div class="stars">
            <h2 class="names" id="sos">Sea of Stars</h2>
            <div>
              <img
                id="sosimg"
                class="bigpics"
                src="../images/Beaches/maldives.jpg"
              />
              <img
                id="sosfood"
                class="foodpics"
                src="../images/Food/Sea of Stars food.jpg"
              />
            </div>
            <img id="sand3" class="sand" src="../images/Beaches/sand.jpg" />
            <h2 id="act3" class="activities">Activities</h2>
            <img
              id="fish"
              class="actpics"
              src="../images/Activities/Fishing.jpg"
            />
            <img
              class="actpics"
              id="stargaze"
              src="../images/Activities/Sea star gazing.jpg"
            />
            <img
              class="actpics"
              id="bonfire"
              src="../images/Activities/Beach Bonfires.jpg"
            />
            <h2 class="reviews">Reviews</h2>
            <img src="../images/Revs/SOS Rev 1.jpg" alt="" />
            <img src="../images/Revs/SOS Rev 2.jpg" alt="" />
            <img src="../images/Revs/SOS Rev 3.jpg" alt="" />
            <img src="../images/Revs/SOS Rev 4.jpg" alt="" />
          </div>
          <div class="copa" id="cb">
            <h2 id="cbname" class="names">Copacabana</h2>
            <div>
              <img id="sand4" class="sand" src="https://bit.ly/3NhBo1R" />
              <img
                class="bigpics"
                id="cbimg"
                src="../images/Beaches/copacabana.jpg"
              />
              <h2 id="act4" class="activities">Activities</h2>
              <div id="cbacts">
                <img
                  class="actpics2"
                  src="../images/Activities/Beach volleyball.jpg"
                />
                <img
                  class="actpics2"
                  src="../images/Activities/Snorkling.jpg"
                />
                <img class="actpics4" src="../images/Activities/Surfing.jpg" />
              </div>
            </div>
            <img
              class="foodpics"
              id="cbfood"
              src="../images/Food/Copacabana food.jpg"
            />
            <h2 class="reviews">Reviews</h2>
            <img src="../images/Revs/Cop Rev 1.jpg" alt="" />
            <img src="../images/Revs/Cop Rev 2.jpg" alt="" />
            <img src="../images/Revs/Cop Rev 3.jpg" alt="" />
            <img src="../images/Revs/Cop Rev 4.jpg" alt="" />
          </div>
          <div class="rena">
            <h2 id="riname" class="names">Renaissance Island</h2>
            <img class="sand" src="../images/Beaches/sand.jpg" />
            <h2 class="activities">Activities</h2>
            <div>
              <img
                class="actpics"
                src="../images/Activities/Flamingo Watching.jpg"
              />
              <img class="actpics" src="../images/Activities/Jeep Safari.jpg" />
              <img
                class="actpics"
                src="../images/Activities/Beach Reading.jpg"
              />
            </div>
            <img
              id="rifood"
              class="foodpics"
              src="../images/Food/Renaissance Island food.jpg"
            />
            <img id="riimg" class="bigpics" src="../images/Beaches/ri.png" />
            <h2 class="reviews">Reviews</h2>
            <img src="../images/Revs/RI Rev 1.jpg" alt="" />
            <img src="../images/Revs/RI Rev 2.jpg" alt="" />
            <img src="../images/Revs/RI Rev 3.jpg" alt="" />
            <img src="../images/Revs/RI Rev 4.jpg" alt="" />
          </div>
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