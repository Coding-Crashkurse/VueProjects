<template>
  <section
    id="home"
    :style="{
      background:
        'linear-gradient(0deg, rgba(0, 0, 0, 0.2), rgba(0, 0, 0, 0.2)),' +
        'url(' +
        require('@/assets/strand.jpeg') +
        ') no-repeat center center fixed',
      height: '100vh',
      backgroundSize: 'cover',
    }"
  >
    <div class="overlay">
      <h1>Dein Traumurlaub</h1>
      <div class="btn_primary">Heute buchen</div>
    </div>
  </section>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Permanent+Marker&display=swap");

* {
  padding: 0;
  margin: 0;
}

body {
  font-family: "Permanent Marker", cursive;
}

#home {
  position: relative;
  z-index: 999;
  width: 100%;
  height: 100vh;
}
.overlay {
  position: absolute;
  color: white;
  text-transform: uppercase;
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
  text-align: center;
}

.overlay h1 {
  padding: 10px 10px;
  border-radius: 10px;
  background: rgba(0, 0, 255, 0.45);
  font-size: 4rem;
}

.btn_primary {
  padding: 15px 20px;
  font-size: 1.5rem;
  margin: 1em auto;
  background-color: #0c2b77;
  color: white;
  border-radius: 3px;
  text-transform: uppercase;
  width: 220px;
  border: 1px solid white;
  cursor: pointer;
  transition: all 0.25s ease-in;
}

.btn_primary:hover {
  color: #0c2b77;
  border: 1px solid #0c2b77;
  background: white;
}
</style>
