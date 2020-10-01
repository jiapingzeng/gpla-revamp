<template>
  <div id="events-container">
    <div class="events-heading-container">
      <h3><u>What's happening</u> at Gracepoint LA</h3>
    </div>
    <div class="events-card-container">
      <div class="events-card">
        <div class="card-image-container">
          <img
            src="https://images.squarespace-cdn.com/content/v1/528d9e1ce4b04fc308327f74/1595456329458-6ZQ5DIMI4O4K5VWYMWWG/ke17ZwdGBToddI8pDm48kLu_kitFPggNFME9L-ll7v1Zw-zPPgdn4jUwVcJE1ZvWEtT5uBSRWt4vQZAgTJucoTqqXjS3CfNDSuuf31e0tVEjmKPDrjOqGQBpsq7WS3xEBQw2tH2SLXcpprSGvfHu4TFvbuqF0GUInBxxtVhBOn4/event1.png"
          />
        </div>
        <div class="card-text-container">
          <h5>Online Sunday Service</h5>
          <p>11AM and 2PM Services</p>
        </div>
      </div>
      <div class="events-card">
        <div class="card-image-container">
          <img
            src="https://images.squarespace-cdn.com/content/v1/528d9e1ce4b04fc308327f74/1595456336665-1I3EGMLHEA590SOLVSBU/ke17ZwdGBToddI8pDm48kLu_kitFPggNFME9L-ll7v1Zw-zPPgdn4jUwVcJE1ZvWEtT5uBSRWt4vQZAgTJucoTqqXjS3CfNDSuuf31e0tVEjmKPDrjOqGQBpsq7WS3xEBQw2tH2SLXcpprSGvfHu4TFvbuqF0GUInBxxtVhBOn4/event2.png"
          />
        </div>
        <div class="card-text-container">
          <h5>Future Bruin Sunday</h5>
          <p>Preview service for the Frosh</p>
        </div>
      </div>
      <div class="events-card">
        <div class="card-image-container">
          <img
            src="https://images.squarespace-cdn.com/content/v1/528d9e1ce4b04fc308327f74/1595456336702-G8KU0W2R9IKAT7ZP8K26/ke17ZwdGBToddI8pDm48kLu_kitFPggNFME9L-ll7v1Zw-zPPgdn4jUwVcJE1ZvWEtT5uBSRWt4vQZAgTJucoTqqXjS3CfNDSuuf31e0tVEjmKPDrjOqGQBpsq7WS3xEBQw2tH2SLXcpprSGvfHu4TFvbuqF0GUInBxxtVhBOn4/event3.png"
          />
        </div>
        <div class="card-text-container">
          <h5>Vision 2020</h5>
          <p>Summer</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
#events-container {
  margin: auto;
  padding: 3em 0 1em 0;
  position: relative;
  width: 100%;
  max-width: 1600px;
  height: 400px;
}

.events-heading-container {
  width: 100%;
  text-align: center;
}

.events-heading-container h3 {
  font-family: "Cabin", "Open Sans", sans-serif;
  font-weight: bold;
  font-size: 2.5em;
  margin: 0 0 1.5em 0;
}

.events-heading-container h3 u {
  text-decoration: underline;
  text-decoration-color: #fb91445c;
}

.events-card-container {
  margin: 0 auto;
  width: 80%;
  max-width: 1000px;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-gap: 2em;
}

.events-card {
  height: 250px;
  box-shadow: 0 3px 6px grey;
  display: grid;
  grid-template-rows: 65% 35%;
}

.events-card .card-image-container {
  width: 100%;
  overflow: hidden;
}

.events-card .card-image-container img {
  width: 100%;
}

.events-card .card-text-container {
  margin: 15px 25px;
}

.events-card .card-text-container h5 {
  font-family: "Cabin", "Open Sans", sans-serif;
  margin: 0;
  font-size: 1.2em;
}

.events-card .card-text-container p {
  font-family: "Cabin", "Open Sans", sans-serif;
  margin: 0;
  font-size: 0.9em;
}
</style>

<script>
export default {
  name: "Events",
};
</script>