<template>
  <div>
    <h1 id="header">Beach Please</h1>
    <div id="titles">
      <div class="names">
        <img class="seashell1" src="../images/seashell.PNG" />
        <h2>Champagne Beach</h2>
        <img class="seashell2" src="../images/seashell.PNG" />
      </div>
      <img class="bigpics" src="../images/champagne beach.jpg" />
      <div class="names">
        <img class="seashell1" src="../images/seashell.PNG" />
        <h2>Ora Beach</h2>
        <img class="seashell2" src="../images/seashell.PNG" />
      </div>
      <img class="bigpics" src="../images/ora beach.jpg" />
      <div class="names">
        <img class="seashell1" src="../images/seashell.PNG" />
        <h2>Sea of Stars</h2>
        <img class="seashell2" src="../images/seashell.PNG" />
      </div>
      <img class="bigpics" src="../images/maldives.jpg" />
      <div class="names">
        <img class="seashell1" src="../images/seashell.PNG" />
        <h2>Copacabana</h2>
        <img class="seashell2" src="../images/seashell.PNG" />
      </div>
      <img class="bigpics" src="../images/copacabana.jpg" />
      <div class="names">
        <img class="seashell1" src="../images/seashell.PNG" />
        <h2>Renaissance Island</h2>
        <img class="seashell2" src="../images/seashell.PNG" />
      </div>
      <img class="bigpics" src="../images/ri.png" />
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
  padding: 4rem;
  font-family: "Ribeye", cursive;
}
h2 {
  color: var(--black);
  font-size: var(--h2);
  text-align: center;
}
.seashell1 {
  width: 10rem;
  height: 10rem;
  float: left;
}
.seashell2 {
  width: 10rem;
  height: 10rem;
  float: right;
  margin-top: -10rem;
}
#titles {
  position: static;
  display: inline;
  margin-top: 10rem;
}
.names {
  margin-top: 5rem;
}
.bigpics {
  margin-top: 5rem;
  width: 100%;
  height: 100rem;
  object-fit: cover;
  margin-top: 10rem;
  margin-bottom: 10rem;
}
</style>
