<template>
  <div class="connect-container">
    <div class="connect-text-container">
      <h1>
        got
        <br />
        <span>questions</span>?
      </h1>
      <p>Just ask! We'd love to connect with you.</p>
      <a href="#">Get Connected</a>
    </div>
    <div class="connect-image">
    </div>
  </div>
</template>

<style scoped>
.connect-container {
  margin: auto;
  width: 100%;
  max-width: 1600px;
  height: 500px;
  display: grid;
  grid-template-columns: 45% 55%;
}

.connect-text-container {
  background-color: rgba(244, 207, 76, 0.6);
  padding-left: 5em;
}

.connect-text-container h1 {
  text-transform: none;
  text-align: left;
  font-family: "Cabin", "Open Sans", sans-serif !important;
  -webkit-text-fill-color: transparent;
  -webkit-text-stroke: 3px white;
  font-size: 5em;
  font-style: normal;
  font-weight: normal;
  color: white;
  margin-bottom: 0;
}

.connect-text-container h1 span {
  font-family: "Cabin", "Open Sans", sans-serif !important;
  text-decoration: underline;
}

.connect-text-container p {
  font-family: "Cabin", "Open Sans", sans-serif !important;
  font-size: 1.3em;
  color: white;
  margin: 2em 0;
}

.connect-text-container a {
  text-transform: uppercase;
  text-decoration: none;
  font-family: "Cabin", "Open Sans", sans-serif !important;
  font-size: 1.2em;
  padding: 0.4em 0.7em;
  border-radius: 50px;
  background-color: white;
  color: #f4cf4c;
}

.connect-image {
  background-image: url("https://images.squarespace-cdn.com/content/v1/528d9e1ce4b04fc308327f74/1599080802999-2ZP23B4E8O7CM9H0GCUP/ke17ZwdGBToddI8pDm48kIpRUFk2zOup_fa9nXlqW8t7gQa3H78H3Y0txjaiv_0fDoOvxcdMmMKkDsyUqMSsMWxHk725yiiHCCLfrh8O1z4YTzHvnKhyp6Da-NYroOW3ZGjoBKy3azqku80C789l0our2fFm0C8uL6iR1T29xI47fnA6c0O4MihZPS7vMcFMt11LJE0p2RKhGyHrOmcD1A/about-connect.png");
  background-position: center;
  background-size: cover;
  overflow: hidden;
}
</style>

<script>
export default {
  name: "Connect",
  mounted() {},
};
</script>