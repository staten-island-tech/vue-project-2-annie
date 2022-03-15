<template>
  <div>
    <h1>Beach Please</h1>
    <h2>Champagne Beach</h2>
    <h2>Ora Beach</h2>
    <h2>Sea of Stars</h2>
    <h2>Copacabana</h2>
    <h2>Renaissance Island</h2>
  </div>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>

<style>
body,
html,
* {
  margin: 0;
  padding: 0;
  font-size: 62.5%;
  box-sizing: border-box;
  background: var(--bg-blue);
}

:root {
  --bg-blue: #f5f6fa;
  --dark-blue: #0c5aaf;
  --light-blue: #a2ccf7;
  --bg-wave: #52b3f3;
  --mid-wave: #4d88c8;
  --fr-wave: #0099ff;
  --footer: #ffffff;
  --white: #0690ff;

  --h1: 15rem;
  --h2: 10rem;
  --h3: 1.5rem;

  --primary: var(--bg-blue);
}

h1 {
  color: var(--bg-blue);
  font-size: var(--h1);
  background: var(--dark-blue);
  text-align: center;
  padding: 4rem;
}
</style>
