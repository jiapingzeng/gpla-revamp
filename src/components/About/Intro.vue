<template>
  <div class="intro-container">
    <div class="circle-convas-container">
      <canvas id="intro-yellow-circle"></canvas>
    </div>
    <div class="intro-image"></div>
    <div class="yellow-overlay"></div>
    <h1><u>about us</u></h1>
  </div>
</template>

<style scoped>
.intro-container {
  position: relative;
  width: 95vw;
  height: 60vh;
  margin-top: 4vh;
}

.circle-convas-container {
  position: absolute;
  top: -4vh;
  right: -30vh;
  width: 50vh;
  height: 50vh;
  z-index: 0;
}

.intro-image {
  position: absolute;
  top: 0px;
  left: 0px;
  width: 100%;
  height: inherit;
  background-image: url("../../assets/About/intro-background.png");
  /*background-image: url("https://images.squarespace-cdn.com/content/v1/528d9e1ce4b04fc308327f74/1594853835441-WCAZF65GVP7HF020CVUL/ke17ZwdGBToddI8pDm48kE1vR9GeFvLGaR9pIrP50dl7gQa3H78H3Y0txjaiv_0fDoOvxcdMmMKkDsyUqMSsMWxHk725yiiHCCLfrh8O1z4YTzHvnKhyp6Da-NYroOW3ZGjoBKy3azqku80C789l0pYhw0hUt3fFBLjZKhYoFXmDEamusJevyRfSrDf0gZeyd-uZZ6n4CIJVqNSgrCeUGg/intro-background-full.png");*/
  background-size: cover;
  background-repeat: no-repeat;
  background-position: 50% 50%;
}

.yellow-overlay {
  position: absolute;
  top: 0px;
  left: 0px;
  width: 100%;
  height: inherit;
  background: linear-gradient(
    180deg,
    rgba(244, 207, 76, 0.7) 0%,
    rgba(244, 207, 76, 0) 0.01%,
    rgba(244, 207, 76, 0.65625) 99.99%
  );
}

.intro-container h1 {
  text-transform: none;
  margin: 0;
  position: absolute;
  left: 0.8em;
  bottom: 0.6em;
  font-family: "Cabin", "Open Sans", sans-serif !important;
  -webkit-text-fill-color: transparent;
  -webkit-text-stroke: 2px white;
  font-size: 6em;
  font-style: normal;
  font-weight: normal;
}

.intro-container h1 u {
  text-decoration: underline;
  text-decoration-color: #fb91445c;
}

@media screen and (max-width: 900px) {
  #intro-container {
    margin-top: 0px;
  }

  .circle-convas-container {
    display: none;
  }

  .intro-image,
  .yellow-overlay {
    width: 100%;
  }
}
</style>

<script>
export default {
  name: "Intro",
  mounted() {
    const c1 = document.getElementById("intro-yellow-circle");
    const cs1 = getComputedStyle(c1.parentElement);
    const ctx1 = c1.getContext("2d");
    const c1width = parseInt(cs1.width);
    const c1height = parseInt(cs1.height);

    // set canvas size
    c1.width = c1width;
    c1.height = c1height;

    // draw circle that fills canvas
    ctx1.beginPath();
    ctx1.arc(c1width / 2, c1height / 2, c1width / 2, 0, 2 * Math.PI);
    ctx1.fillStyle = "#f4cf4c";
    ctx1.fill();
    ctx1.strokeStyle = "#f4cf4c";
    ctx1.stroke();
  }
};
</script>