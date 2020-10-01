<template>
  <div class="church-container">
    <img
      src="https://images.squarespace-cdn.com/content/v1/528d9e1ce4b04fc308327f74/1601488331296-W8SSSR5TXA7YNHZ0YC7I/ke17ZwdGBToddI8pDm48kFrMQGbB3Kx_IPnSET4NXL97gQa3H78H3Y0txjaiv_0fDoOvxcdMmMKkDsyUqMSsMWxHk725yiiHCCLfrh8O1z5QHyNOqBUUEtDDsRWrJLTm_afzcbrtRvP0u-2GkeQ0MMpgjVImuQpaDeN-3jK9zCDUgblYj_oJjO16RhY5X8I3/story-arrow.png"
    />
    <div class="church-text-container">
      <h3>
        The
        <u>story</u>
        <br />behind <br />our church.
      </h3>
      <p>
        In 2013, a team of staff moved from the Bay Area with a vision of
        starting an Acts 2 church in Los Angeles. For many of us, college was a
        transformative time. Jesus' call grabbed a hold of our hearts as we
        experienced the power of God's word and the richness of a biblical
        community. It's an experience we want to pass on to others, so we plant
        churches in college towns and try to recreate the same tight knit
        community described in Acts 2.
      </p>
    </div>
    <div class="church-video-container">
      <iframe src="https://www.youtube.com/embed/sxlbN8MtjN4"></iframe>
    </div>
  </div>
</template>

<style scoped>
.church-container {
  margin: auto;
  padding: 5em 0;
  position: relative;
  width: 100vw;
  max-width: 1600px;
  height: 500px;
  display: grid;
  grid-template-columns: 40% 50%;
  grid-gap: 3vw;
}

.church-container img {
  position: absolute;
  width: 250px;
  transform: rotate(-10deg);
  top: 80px;
  left: 400px;
}

.church-text-container {
  height: 100%;
  margin-left: 100px;
  display: grid;
  grid-template-rows: 40% 50%;
  grid-gap: 3em;
  align-content: center;
}

.church-text-container h3 {
  margin: 0;
  line-height: 1.1em;
  text-align: left;
  text-transform: none;
  font-weight: normal;
  font-family: "Cabin", "Open Sans", sans-serif !important;
  font-size: 4em;
  letter-spacing: normal !important;
}

.church-text-container p {
  font-weight: normal;
  font-family: "Cabin", "Open Sans", sans-serif !important;
  font-size: 1.3em;
}

.church-text-container h3 u {
  text-decoration: underline;
  text-decoration-color: #fb91445c;
}

.church-video-container {
  position: relative;
  padding-bottom: 56.25%;
  height: 0;
}

.church-video-container iframe {
  border: none;
  position: absolute;
  top: 5%;
  left: 0;
  width: 100%;
  height: 100%;
}
</style>

<script>
export default {
  name: "Church",
  mounted() {},
};
</script>