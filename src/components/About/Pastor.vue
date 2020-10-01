<template>
  <div class="pastor-container">
    <div class="pastor-canvas-container">
      <canvas id="pastor-dotted-background"></canvas>
    </div>
    <div class="pastor-flex-container">
      <div class="pastor-picture-container">
        <img
          src="https://images.squarespace-cdn.com/content/v1/528d9e1ce4b04fc308327f74/1594939775162-9M3UBF7N6T01RWVEJ9QU/ke17ZwdGBToddI8pDm48kHldqyjDwaeS7kYSmaCmglZ7gQa3H78H3Y0txjaiv_0fDoOvxcdMmMKkDsyUqMSsMWxHk725yiiHCCLfrh8O1z5QHyNOqBUUEtDDsRWrJLTmxIv-U8QkF7Aqck8oUqvfAAOvy8DUzW3k1lLKw2Wu7uCpNBpi2q7oKJPU7loduYjD/manny-sunny.png"
        />
        <div class="pastor-picture-caption">
          <h5>Manny &amp; Sunny Kim</h5>
          <p>Southern California Regional Pastor</p>
        </div>
      </div>
    </div>
    <div class="pastor-text-container">
      <h3>
        Meet our
        <u>pastor.</u>
      </h3>
      <h4>SOME BACKGROUND</h4>
      <p>Manny and Sunny Kim have been faithfully serving in college ministry for over 25 years. They have 2 daughters, Corrie and Naomi. They oversee the Gracepoint churches in the Southern California region from Irvine, where they currently live.</p>
      <h4>FUN FACTS</h4>
      <p>Manny: Best known for his basketball and amazing storytelling skills.<br>Sunny: Her real name is not actually Sunny, but she got her name because she was always smiling.</p>
    </div>
  </div>
</template>

<style scoped>
.pastor-container {
  margin: auto;
  position: relative;
  width: 100%;
  max-width: 1600px;
  height: 600px;
  display: grid;
  grid-template-columns: 40% 60%;
}

.pastor-canvas-container {
  position: absolute;
  width: 100%;
  height: inherit;
  z-index: 0;
}

.pastor-flex-container {
  display: grid;
  place-items: center;
  padding-bottom: 2.5em;
  z-index: 1;
}

.pastor-picture-container {
  width: 60%;
  background-color: white;
  box-shadow: 1.5px 5px 8px lightgrey;
}

.pastor-picture-container img {
  width: 85%;
  margin: 7.5% 7.5% 0 7.5%;
}

.pastor-picture-caption {
  text-align: center;
}

.pastor-picture-caption h5 {
  font-family: "Cabin", "Open Sans", sans-serif !important;
  font-size: 2em;
  margin-top: 0.2em;
  margin-bottom: 0.2em;
}

.pastor-picture-caption p {
  font-family: "Cabin", "Open Sans", sans-serif !important;
  font-size: 1.2em;
  margin-top: 0.1em;
}

.pastor-text-container {
  margin: 0 5em 0 5em;
  padding-bottom: 4em;
  z-index: 1;
}

.pastor-text-container h3 {
  text-align: right;
  text-transform: none;
  font-weight: normal;
  font-family: "Cabin", "Open Sans", sans-serif !important;
  font-size: 4em;
  margin-top: 1em !important;
  letter-spacing: normal !important;
}

.pastor-text-container h3 u {
  text-decoration: underline;
  text-decoration-color: #fb91445c;
}

.pastor-text-container h4 {
  margin: 2em 0 0 0;
  text-align: left;
  font-weight: normal;
  font-family: "Cabin", "Open Sans", sans-serif !important;
  font-size: 1.6em;
  color: #f4cf4c;
  text-transform: uppercase;
}

.pastor-text-container p {
  margin: 0;
  text-align: left;
  font-family: "Cabin", "Open Sans", sans-serif !important;
  font-size: 1.2em;
}
</style>

<script>
export default {
  name: "Pastor",
  mounted() {
    const c3 = document.getElementById("pastor-dotted-background");
    const cs3 = getComputedStyle(c3.parentElement);
    const ctx3 = c3.getContext("2d");
    const c3width = parseInt(cs3.width);
    const c3height = parseInt(cs3.height);

    c3.width = c3width;
    c3.height = c3height;

    ctx3.setLineDash([0.5, 6]);
    ctx3.beginPath();
    for (let i = 0; i < c3height; i += 6) {
      ctx3.moveTo((i % 12) / 2, i);
      ctx3.lineTo(c3width, i);
    }
    ctx3.stroke();
  },
};
</script>