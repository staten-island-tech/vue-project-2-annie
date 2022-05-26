<template>
  <body id="body">
    <div>
      <h1 id="maintitle">Beach Please</h1>
       <button class="button" @click="theme">Dark Mode</button>
      <div id="gallery">
        <div id="titles">
          <div class="cham">
            <h2 class="names" id="cb">Champagne Beach
            </h2>
            <div>
              <img
                id="chamimg"
                class="bigpics"
                src="../images/Beaches/champagne beach.jpg"
                alt="Image of Champagne Beach"
              />
              <img
                id="chamfood"
                class="foodpics"
                src="../images/Food/Champagne beach food.jpg"
                alt="Image of Champagne Beach food"
              />
            </div>
            <img class="sand" src="../images/Beaches/sand.jpg" alt="Image of sand"/>
            <h3 class="activities">Activities</h3>
            <div>
              <h4 class="actdesc">
                Have some fun at Beach Zumba! Dance with your friends all day.
              </h4>
              <h4 class="actdesc">
                Play in the sand and make some beautiful sand art!
              </h4>
              <h4 class="actdesc">
                Toss around a frsibee with your friends and family to stay
                active!
              </h4>
            </div>
            <div>
               <cld-transformation height="480" width="480" crop="fill" />
            <div>
              <img class="actpics" src="../images/Activities/Beach zumba.jpg" alt="Beach zumba image" />
              <img class="actpics" src="../images/Activities/Sand art.jpg" alt="Sand art image"/>
              <img class="actpics" src="../images/Activities/Frisbee.jpg" alt="Frisbee image"/>
            </div>
            </div>
            <h3 class="reviews">Reviews</h3>
            <img class="rev1" src="../images/Revs/Cham Rev 1.jpg" alt="Review #1 on Champagne Beach" />
            <img class="rev2" src="../images/Revs/Cham Rev 2.jpg" alt="Review #2 on Champagne Beach" />
            <img class="rev3" src="../images/Revs/Cham Rev 3.jpg" alt="Review #3 on Champagne Beach" />
            <img class="rev4" src="../images/Revs/Cham Rev 4.jpg" alt="Review #4 on Champagne Beach" />
          </div>
          <div class="ora" id="ob">
            <h2 id="obname" class="names">Ora Beach</h2>
            <div>
              <img id="sand2" class="sand" src="https://bit.ly/3NhBo1R" alt="Image of Sand"/>
              <img
                class="bigpics"
                id="oraimg"
                src="../images/Beaches/ora beach.jpg"
                alt="Image of Ora Beach"
              />
              <h3 id="act2" class="activities">Activities</h3>
              <div id="oraacts">
                <div>
                  <p class="actdesc2">
                    Have fun and play water polo at the beach with others!
                  </p>
                  <p class="actdesc2">
                    Make custom jewelry out of seashells found at the beach!
                  </p>
                  <p class="actdesc2">
                    Participate in the local sand castle building contest on the
                    shore!
                  </p>
                </div>
                <div id="actdiv2">
                  <div>
                  <cld-transformation height="480" width="480" crop="fill" />
                  <img
                    class="actpics2"
                    src="../images/Activities/Water Polo.jpg"
                    alt="Water polo image"
                  />
                  <img
                    class="actpics2"
                    src="../images/Activities/Jewelry Making.jpg"
                    alt="Jewelry making image"
                  />
                  <img
                    class="actpics2"
                    src="../images/Activities/Castle construction.jpg"
                    alt="Castle construction image"
                  />
                </div>
                </div>
              </div>
            </div>
            <img
              class="foodpics"
              id="orafood"
              src="../images/Food/Ora beach food.jpg"
              alt="Image of Ora Beach food"
            />
            <h3 class="reviews">Reviews</h3>
            <img class="rev1" src="../images/Revs/Ora Rev 1.jpg" alt="Review #1 on Ora Beach" />
            <img class="rev2" src="../images/Revs/Ora Rev 2.jpg" alt="Review #2 on Ora Beach" />
            <img class="rev3" src="../images/Revs/Ora Rev 3.jpg" alt="Review #3 on Ora Beach" />
            <img class="rev4" src="../images/Revs/Ora Rev 4.jpg" alt="Review #4 on Ora Beach" />
          </div>
          <div class="stars">
            <h2 class="names" id="sos">Sea of Stars</h2>
            <div>
              <img
                id="sosimg"
                class="bigpics"
                src="../images/Beaches/maldives.jpg"
                alt="Image of Sea of Stars"
              />
              <img
                id="sosfood"
                class="foodpics"
                src="../images/Food/Sea of Stars food.jpg"
                alt="Image of Sea of Stars food"
              />
            </div>
            <img id="sand3" class="sand" src="../images/Beaches/sand.jpg" alt="Image of sand"/>
            <h3 id="act3" class="activities">Activities</h3>
            <div>
              <h4 class="actdesc3" id="fishdesc">
                Fish from the pier or a boat! Teachers are available if needed.
              </h4>
              <h4 class="actdesc3" id="stardesc">
                Watch the signature glowing "stars" and take in the beauty!
              </h4>
              <h4 class="actdesc3" id="firedesc">
                Cozy up to a bonfire on the beach and have a tasty barbecue!
              </h4>
            </div>
              <div>
                  <cld-transformation height="480" width="480" crop="fill" />
            <img
              id="fish"
              class="actpics3"
              src="../images/Activities/Fishing.jpg"
              alt="Fishing image"
            />
            <img
              class="actpics3"
              id="stargaze"
              src="../images/Activities/Sea star gazing.jpg"
              alt="Sea star gazing image"
            />
            <img
              class="actpics3"
              id="bonfire"
              src="../images/Activities/Beach Bonfires.jpg"
              alt="Beach bonfires image"
            />
              </div>
            <h3 class="reviews" id="sosrev">Reviews</h3>
            <img class="rev1" src="../images/Revs/SOS Rev 1.jpg" alt="Review #1 on Sea of Stars" />
            <img class="rev2" src="../images/Revs/SOS Rev 2.jpg" alt="Review #2 on Sea of Stars" />
            <img class="rev3" src="../images/Revs/SOS Rev 3.jpg" alt="Review #3 on Sea of Stars" />
            <img class="rev4" src="../images/Revs/SOS Rev 4.jpg" alt="Review #4 on Sea of Stars" />
          </div>
          <div class="copa" id="cb">
            <h2 id="cbname" class="names">Copacabana</h2>
            <div>
              <img id="sand4" class="sand" src="https://bit.ly/3NhBo1R" alt="Image of sand"/>
              <img
                class="bigpics"
                id="cbimg"
                src="../images/Beaches/copacabana.jpg"
                alt="Image of Copacabana Beach"
              />
              <h3 id="act4" class="activities">Activities</h3>
              <div id="cbacts">
                <div>
                  <p class="actdesc2">
                    Compete by yourself or in teams and play volleyball on the
                    beach!
                  </p>
                  <p class="actdesc2">
                    Discover and interact with the aquatic scenery while
                    snorkling!
                  </p>
                  <p class="actdesc2">
                    Go for surfing and have fun riding waves of all different
                    sizes!
                  </p>
                </div>
                <div id="actdiv2">
                  <div>
                  <cld-transformation height="480" width="480" crop="fill" />
                  <img
                    class="actpics4"
                    src="../images/Activities/Beach volleyball.jpg"
                    alt="Beach volleyball image"
                  />
                  <img
                    class="actpics4"
                    src="../images/Activities/Snorkling.jpg"
                    alt="Snorkling image"
                  />
                  <img
                    class="actpics4"
                    src="../images/Activities/Surfing.jpg"
                    alt="Surfing image"
                  />
                </div>
                </div>
              </div>
            </div>
            <img
              class="foodpics"
              id="cbfood"
              src="../images/Food/Copacabana food.jpg"
              alt="Image of Copacabana Beach food"
            />
            <h3 class="reviews">Reviews</h3>
            <img class="rev1" src="../images/Revs/Cop Rev 1.jpg" alt="Review #1 on Copacabana Beach" />
            <img class="rev2" src="../images/Revs/Cop Rev 2.jpg" alt="Review #2 on Copacabana Beach" />
            <img class="rev3" src="../images/Revs/Cop Rev 3.jpg" alt="Review #3 on Copacabana Beach" />
            <img class="rev4" src="../images/Revs/Cop Rev 4.jpg" alt="Review #4 on Copacabana Beach" />
          </div>
          <div class="rena">
            <h2 id="riname" class="names">Renaissance Island</h2>
            <img class="sand" src="../images/Beaches/sand.jpg" alt="Image of sand"/>
            <h3 class="activities">Activities</h3>
            <h4 class="actdesc5">
              The island is known for its flamingos, so watch them here!
            </h4>
            <h4 class="actdesc5">
              Enjoy a thrilling beachside Jeep Safari tour!
            </h4>
            <h4 class="actdesc5">
              Relax by the shore and curl up with a book to wind down.
            </h4>
              <div>
                  <cld-transformation height="480" width="480" crop="fill" />
            <div>
              <img
                class="actpics5"
                src="../images/Activities/Flamingo Watching.jpg"
                alt="Flamingo watching image"
              />
              <img
                class="actpics5"
                src="../images/Activities/Jeep Safari.jpg"
                alt="Jeep safari image"
              />
              <img
                class="actpics5"
                src="../images/Activities/Beach Reading.jpg"
                alt="Beach reading image"
              />
            </div>
            </div>
            <img
              id="rifood"
              class="foodpics"
              src="../images/Food/Renaissance Island food.jpg"
              alt="Image of Renaissance Island food"
            />
            <img id="riimg" class="bigpics" src="../images/Beaches/ri.png" alt="Image of Renaissance Island"/>
            <h3 class="reviews">Reviews</h3>
            <img class="rev1" src="../images/Revs/RI Rev 1.jpg" alt="Review #1 on Renaissance Island" />
            <img class="rev2" src="../images/Revs/RI Rev 2.jpg" alt="Review #2 on Renaissance Island" />
            <img class="rev3" src="../images/Revs/RI Rev 3.jpg" alt="Review #3 on Renaissance Island" />
            <img class="rev4" src="../images/Revs/RI Rev 4.jpg" alt="Review #4 on Renaissance Island" />
          </div>
        </div>
      </div>
    </div>
  </body>
</template>

<script>

export default {
  name: "IndexPage",
  mounted: function () {
    this.startAnimations();
    this.flip();
  },
  methods: {
    startAnimations: function () {
      const tl = this.$gsap.timeline({ scrollTrigger: "#gallery", delay: 0.5 });
     this.$gsap.to("#maintitle", { duration: 1, color: "white" });
      tl.from("#gallery", { opacity: 0, duration: 3 });
    },
    flip: function () {},
    
    theme(){
       if (this.theme === "darkmode") {
        this.theme = ":root";
      } else {
        this.theme = "darkmode";
    }
  },
  }
}
</script>

<style>
@import "style.css";

</style>
