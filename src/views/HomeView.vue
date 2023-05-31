<script setup>
</script>

<template>
  <main class="intro">
    <div class="intro_info">
      <p class="subtitle">New Arrival</p>
      <h1>
        Discover Our
        <br>
        New Collection
      </h1>
      <p class="text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut elit tellus, luctus nec ullamcorper
        mattis.</p>
      <button>BUY NOW</button>
    </div>
  </main>
</template>


<style>
.intro {
  background-image: url('../assets/img/intro.png');
  background-repeat: no-repeat;
  background-position: center;
  background-color: rgba(122, 56, 56, 0.114);
  display: block;
  position: absolute;
  left: 0;
  right: 0;
  min-width: 1220px;
  max-width: 1280px;
  height: 750px;
  width: 100%;
  margin: auto;
  margin-top: 20px;
}

.intro_info {
  background: #DFE9F4;
  border-radius: 10px;
  padding: 39px;
  width: 50%;
  position: relative;
  top: 20%;
  left: 40%;
}

.subtitle {
  font-family: Montserrat;
  font-size: 16px;
  font-weight: 600;
  line-height: 20px;
  letter-spacing: 3px;
  text-align: left;
}

h1 {
  font-family: Montserrat;
  font-size: 52px;
  font-weight: 700;
  line-height: 65px;
  letter-spacing: 0px;
  text-align: left;
  color: #054C73;
  margin-top: 20px;
  margin-bottom: 10px;
}

.text {
  font-family: Montserrat;
  font-size: 18px;
  font-weight: 500;
  line-height: 39px;
  letter-spacing: 0px;
  text-align: left;
}

button {
  font-family: Montserrat;
  font-size: 16px;
  font-weight: 700;
  line-height: 20px;
  letter-spacing: 0px;
  text-align: left;
  color: #ffff;
  border-radius: 50px;
  padding: 25px 72px;
  background: #054C73;
  border: none;
  margin-top: 30px;
}
</style>