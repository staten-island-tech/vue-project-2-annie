<template>
  <div>
    <body
      id="background"
      background="https://wallpaperforu.com/wp-content/uploads/2020/07/marble-wallpaper-200714140305221920x1200.jpg"
    />
    <h1 id="header">Beach Please</h1>
    <div id="titles">
      <div class="shells">
        <img class="seashell1" src="../images/seashell.PNG" />
        <img class="seashell2" src="../images/seashell.PNG" />
      </div>
      <div class="cham">
        <h2 class="names">Champagne Beach</h2>
        <img class="bigpics" src="../images/champagne beach.jpg" />
      </div>
      <div class="ora">
        <h2 class="names">Ora Beach</h2>
        <img class="bigpics" src="../images/ora beach.jpg" />
      </div>
      <div class="stars">
        <h2 class="names">Sea of Stars</h2>
        <img class="bigpics" src="../images/maldives.jpg" />
      </div>
      <div class="copa">
        <h2 class="names">Copacabana</h2>
        <img class="bigpics" src="../images/copacabana.jpg" />
      </div>
      <div class="rena">
        <h2 class="names">Renaissance Island</h2>
        <img class="bigpics" src="../images/ri.png" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Ribeye&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Readex+Pro:wght@200&display=swap");
body,
html,
* {
  margin: 0;
  padding: 0;
  font-size: 62.5%;
  box-sizing: border-box;
  background: var(--bg-blue);
  background-image: url("https://wallpaperforu.com/wp-content/uploads/2020/07/marble-wallpaper-200714140305221920x1200.jpg");
  font-family: "Readex Pro", sans-serif;
}

:root {
  --bg-blue: #f5f6fa;
  --dark-blue: #0c5aaf;
  --light-blue: #a2ccf7;
  --bg-wave: #52b3f3;
  --mid-wave: #4d88c8;
  --fr-wave: #0099ff;
  --footer: #ffffff;
  --black: #000000;
  --white: #0690ff;

  --h1: 15rem;
  --h2: 8rem;
  --h3: 1.5rem;

  --primary: var(--bg-blue);
}

h1 {
  color: var(--bg-blue);
  font-size: var(--h1);
  background: var(--dark-blue);
  text-align: center;
  width: 170rem;
  height: 30rem;
  padding: 4rem;
  font-family: "Ribeye", cursive;
  border-radius: 3rem;
  margin-left: 5.5%;
  margin-top: 8rem;
}
h2 {
  color: var(--black);
  font-size: var(--h2);
  text-align: center;
}
#background {
  position: absolute;
}
.seashell1 {
  width: 20rem;
  height: 20rem;
  float: left;
  margin-top: -10rem;
}
.seashell2 {
  width: 20rem;
  height: 20rem;
  float: right;
  margin-top: -10rem;
}
#titles {
  position: static;
  display: inline;
  margin-top: 10rem;
}
.names {
  margin-top: 10rem;
}
.bigpics {
  margin-top: 5rem;
  width: 100%;
  height: 100rem;
  object-fit: cover;
  margin-top: 10rem;
}
</style>