<template>
  <body id="body">
    <div>
      <h1 id="maintitle">Beach Please</h1>
      <div id="gallery">
        <input
          @change="toggleTheme"
          id="checkbox"
          type="checkbox"
          class="switch-checkbox"
        />
        <label for="checkbox" class="switch-label">
          <span>Switch</span>
          <span>Theme</span>
          <div
            class="switch-toggle"
            :class="{ 'switch-toggle-checked': userTheme === 'dark-theme' }"
          ></div>
        </label>
        <div id="titles">
          <div class="cham">
            <h2 class="names" id="cb">Champagne Beach</h2>
            <div>
              <img
                id="chamimg"
                class="bigpics"
                src="~../assets/public/images/Beaches/champagnebeach.jpg"
                alt="Image of Champagne Beach"
              />
              <img
                id="chamfood"
                class="foodpics"
                src="~..\assets\public\images\Food\Champagne beach food.jpg"
                alt="Image of Champagne Beach food"
              />
            </div>
            <img
              class="sand"
              src="~..\assets\public\images\Beaches\sand.jpg"
              alt="Image of sand"
            />
            <h3 class="activities">Activities</h3>
            <div>
              <h4 class="actdesc">
                Have some fun at Beach Zumba! Dance with your friends!
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
                <img
                  class="actpics"
                  src="~..\assets\public\images\Activities\Beach zumba.jpg"
                  alt="Beach zumba image"
                />
                <img
                  class="actpics"
                  src="~..\assets\public\images\Activities\Sand art.jpg"
                  alt="Sand art image"
                />
                <img
                  class="actpics"
                  src="~..\assets\public\images\Activities\Frisbee.jpg"
                  alt="Frisbee image"
                />
              </div>
            </div>
            <h3 class="reviews">Reviews</h3>
            <div id="chamrevsdiv">
              <img
                class="rev1"
                src="~..\assets\public\images\Revs\Cham-Rev-1.jpg"
                alt="Review #1 on Champagne Beach"
              />
              <img
                class="rev2"
                src="~..\assets\public\images\Revs\Cham Rev 2.jpg"
                alt="Review #2 on Champagne Beach"
              />
              <img
                class="rev3"
                src="~..\assets\public\images\Revs\Cham Rev 3.jpg"
                alt="Review #3 on Champagne Beach"
              />
              <img
                class="rev4"
                src="~..\assets\public\images\Revs\Cham Rev 4.jpg"
                alt="Review #4 on Champagne Beach"
              />
            </div>
          </div>
          <div class="ora" id="ob">
            <h2 id="obname" class="names">Ora Beach</h2>
            <div>
              <img
                id="sand2"
                class="sand"
                src="https://bit.ly/3NhBo1R"
                alt="Image of Sand"
              />
              <img
                class="bigpics"
                id="oraimg"
                src="~../assets/public/images/Beaches/ora beach.jpg"
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
                      src="~..\assets\public\images\Activities\Water polo.jpg"
                      alt="Water polo image"
                    />
                    <img
                      class="actpics2"
                      src="~..\assets\public\images\Activities\Jewelry Making.jpg"
                      alt="Jewelry making image"
                    />
                    <img
                      class="actpics2"
                      src="~..\assets\public\images\Activities\Castle construction.jpg"
                      alt="Castle construction image"
                    />
                  </div>
                </div>
              </div>
            </div>
            <img
              class="foodpics"
              id="orafood"
              src="~..\assets\public\images\Food\Ora beach food.jpg"
              alt="Image of Ora Beach food"
            />
            <h3 class="reviews">Reviews</h3>
            <div id="orarevsdiv">
              <img
                class="rev1"
                src="~..\assets\public\images\Revs\Ora Rev 1.jpg"
                alt="Review #1 on Ora Beach"
              />
              <img
                class="rev2"
                src="~..\assets\public\images\Revs\Ora Rev 2.jpg"
                alt="Review #2 on Ora Beach"
              />
              <img
                class="rev3"
                src="~..\assets\public\images\Revs\Ora Rev 3.jpg"
                alt="Review #3 on Ora Beach"
              />
              <img
                class="rev4"
                src="~..\assets\public\images\Revs\Ora Rev 4.jpg"
                alt="Review #4 on Ora Beach"
              />
            </div>
          </div>
          <div class="stars">
            <h2 class="names" id="sos">Sea of Stars</h2>
            <div>
              <img
                id="sosimg"
                class="bigpics"
                src="~../assets/public/images/Beaches/maldives.jpg"
                alt="Image of Sea of Stars"
              />
              <img
                id="sosfood"
                class="foodpics"
                src="~..\assets\public\images\Food\Sea of Stars food.jpg"
                alt="Image of Sea of Stars food"
              />
            </div>
            <img
              id="sand3"
              class="sand"
              src="~..\assets\public\images\Beaches\sand.jpg"
              alt="Image of sand"
            />
            <h3 id="act3" class="activities">Activities</h3>
            <div>
              <h4 class="actdesc3" id="fishdesc">
                Fish from the pier or a boat! Teachers are available if needed.
              </h4>
              <h4 class="actdesc3" id="stardesc">
                Watch the glowing "stars" and take in the beauty!
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
                src="~..\assets\public\images\Activities\Fishing.jpg"
                alt="Fishing image"
              />
              <img
                class="actpics3"
                id="stargaze"
                src="~..\assets\public\images\Activities\Sea star gazing.jpg"
                alt="Sea star gazing image"
              />
              <img
                class="actpics3"
                id="bonfire"
                src="~..\assets\public\images\Activities\Beach Bonfires.jpg"
                alt="Beach bonfires image"
              />
            </div>
            <h3 class="reviews" id="sosrev">Reviews</h3>
            <div id="sosrevsdiv">
              <img
                class="rev1"
                src="~..\assets\public\images\Revs\SOS Rev 1.JPG"
                alt="Review #1 on Sea of Stars"
              />
              <img
                class="rev2"
                src="~..\assets\public\images\Revs\SOS Rev 2.JPG"
                alt="Review #2 on Sea of Stars"
              />
              <img
                class="rev3"
                src="~..\assets\public\images\Revs\SOS Rev 3.JPG"
                alt="Review #3 on Sea of Stars"
              />
              <img
                class="rev4"
                src="~..\assets\public\images\Revs\SOS Rev 4.JPG"
                alt="Review #4 on Sea of Stars"
              />
            </div>
          </div>
          <div class="copa" id="cb">
            <h2 id="cbname" class="names">Copacabana</h2>
            <div>
              <img
                id="sand4"
                class="sand"
                src="https://bit.ly/3NhBo1R"
                alt="Image of sand"
              />
              <img
                class="bigpics"
                id="cbimg"
                src="~../assets/public/images/Beaches/copacabana.jpg"
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
                      src="~..\assets\public\images\Activities\Beach volleyball.jpg"
                      alt="Beach volleyball image"
                    />
                    <img
                      class="actpics4"
                      src="~..\assets\public\images\Activities\Snorkling.jpg"
                      alt="Snorkling image"
                    />
                    <img
                      class="actpics4"
                      src="~..\assets\public\images\Activities\Surfing.jpg"
                      alt="Surfing image"
                    />
                  </div>
                </div>
              </div>
            </div>
            <img
              class="foodpics"
              id="cbfood"
              src="~..\assets\public\images\Food\Copacabana food.jpg"
              alt="Image of Copacabana Beach food"
            />
            <h3 class="reviews">Reviews</h3>
            <div id="coprevsdiv">
              <img
                class="rev1"
                src="~..\assets\public\images\Revs\Cop Rev 1.JPG"
                alt="Review #1 on Copacabana Beach"
              />
              <img
                class="rev2"
                src="~..\assets\public\images\Revs\Cop Rev 2.JPG"
                alt="Review #2 on Copacabana Beach"
              />
              <img
                class="rev3"
                src="~..\assets\public\images\Revs\Cop Rev 3.JPG"
                alt="Review #3 on Copacabana Beach"
              />
              <img
                class="rev4"
                src="~..\assets\public\images\Revs\Cop Rev 4.JPG"
                alt="Review #4 on Copacabana Beach"
              />
            </div>
          </div>
          <div class="rena">
            <h2 id="riname" class="names">Renaissance Island</h2>
            <img
              class="sand"
              src="~..\assets\public\images\Beaches\sand.jpg"
              alt="Image of sand"
            />
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
                  src="~..\assets\public\images\Activities\Flamingo Watching.jpg"
                  alt="Flamingo watching image"
                />
                <img
                  class="actpics5"
                  src="~..\assets\public\images\Activities\Jeep Safari.jpg"
                  alt="Jeep safari image"
                />
                <img
                  class="actpics5"
                  src="~..\assets\public\images\Activities\Beach Reading.jpg"
                  alt="Beach reading image"
                />
              </div>
            </div>
          </div>
          <img
            id="rifood"
            class="foodpics"
            src="~..\assets\public\images\Food\Renaissance Island food.jpg"
            alt="Image of Renaissance Island food"
          />
          <img
            id="riimg"
            class="bigpics"
            src="~../assets/public/images/Beaches/ri.png"
            alt="Image of Renaissance Island"
          />
          <h3 class="reviews">Reviews</h3>
          <div id="rirevsdiv">
            <img
              class="rev1"
              src="~../assets/public/images/Revs/RI Rev 1.jpg"
              alt="Review #1 on Renaissance Island"
            />
            <img
              class="rev2"
              src="~../assets/public/images/Revs/RI Rev 2.jpg"
              alt="Review #2 on Renaissance Island"
            />
            <img
              class="rev3"
              src="~../assets/public/images/Revs/RI Rev 3.jpg"
              alt="Review #3 on Renaissance Island"
            />
            <img
              class="rev4"
              src="~../assets/public/images/Revs/RI Rev 4.jpg"
              alt="Review #4 on Renaissance Island"
            />
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
    const initUserTheme = this.getTheme() || this.getMediaPreference();
    this.setTheme(initUserTheme);
  },
  data() {
    return {
      userTheme: "light-theme",
    };
  },
  methods: {
    setTheme(theme) {
      localStorage.setItem("user-theme", theme);
      this.userTheme = theme;
      document.documentElement.className = theme;
    },
    toggleTheme() {
      const activeTheme = localStorage.getItem("user-theme");
      if (activeTheme === "light-theme") {
        this.setTheme("dark-theme");
      } else {
        this.setTheme("light-theme");
      }
    },
    getMediaPreference() {
      const hasDarkPreference = window.matchMedia(
        "(prefers-color-scheme: dark)"
      ).matches;
      if (hasDarkPreference) {
        return "dark-theme";
      } else {
        return "light-theme";
      }
    },
    getTheme() {
      return localStorage.getItem("user-theme");
    },
    startAnimations: function () {
      const tl = this.$gsap.timeline({ scrollTrigger: "#gallery", delay: 0.5 });
      this.$gsap.to("#maintitle", { duration: 1 });
      tl.from("#gallery", { opacity: 0, duration: 3 });
      this.$gsap.from("#chamrevsdiv", {
        scrollTrigger: "#chamrevsdiv",
        opacity: 0,
        duration: 1.5,
        x: 500,
        rotation: 360,
      });
      this.$gsap.from("#orarevsdiv", {
        scrollTrigger: "#orarevsdiv",
        opacity: 0,
        duration: 1.5,
        y: 500,
      });
      this.$gsap.from("#sosrevsdiv", {
        scrollTrigger: "#sosrevsdiv",
        opacity: 0,
        duration: 1.5,
        y: 500,
        x: 500,
        rotation: 90,
      });
      this.$gsap.from("#coprevsdiv", {
        scrollTrigger: "#coprevsdiv",
        opacity: 0,
        duration: 1.5,
        y: 500,
      });
      this.$gsap.from("#rirevsdiv", {
        scrollTrigger: "#rirevsdiv",
        opacity: 0,
        duration: 1.5,
        x: 500,
        rotation: 360,
      });
    },
  },
};
</script>

<style>
@import "style.css";
</style>
