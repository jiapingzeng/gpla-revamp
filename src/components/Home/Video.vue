<template>
  <div id="video-container">
    <h3>What are <u>Sundays</u> like?</h3>

    <!-- icon from Font Awesome https://fontawesome.com/icons/play-circle?style=regular -->
    <!-- TODO: video lightbox -->
    <a
      href="https://www.youtube.com/watch?v=sxlbN8MtjN4&feature=emb_logo"
      target="_blank"
      ><svg
        aria-hidden="true"
        focusable="false"
        data-prefix="far"
        data-icon="play-circle"
        class="svg-inline--fa fa-play-circle fa-w-16"
        role="img"
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 512 512"
      >
        <path
          fill="currentColor"
          d="M371.7 238l-176-107c-15.8-8.8-35.7 2.5-35.7 21v208c0 18.4 19.8 29.8 35.7 21l176-101c16.4-9.1 16.4-32.8 0-42zM504 256C504 119 393 8 256 8S8 119 8 256s111 248 248 248 248-111 248-248zm-448 0c0-110.5 89.5-200 200-200s200 89.5 200 200-89.5 200-200 200S56 366.5 56 256z"
        ></path></svg
    ></a>
  </div>
</template>

<style scoped>
#video-container {
  margin: auto;
  padding: 3em 0;
  position: relative;
  width: 100%;
  max-width: 1600px;
  height: 250px;
  background-image: url("https://images.squarespace-cdn.com/content/v1/528d9e1ce4b04fc308327f74/1601499567893-MVUWZCJ85VOT767K23EO/ke17ZwdGBToddI8pDm48kCdOXSNebqOmJMe5cGNKviAUqsxRUqqbr1mOJYKfIPR7LoDQ9mXPOjoJoqy81S2I8N_N4V1vUb5AoIIIbLZhVYwL8IeDg6_3B-BRuF4nNrNcQkVuAT7tdErd0wQFEGFSnCfPlbvn_s1vhby9uaQ7tg8PW-lwbKz20EJqNeVKYyJ8VEkayCEk8IjOtvSHEANkjg/video-background.png");
  background-repeat: no-repeat;
  background-size: 110%;
  background-position: center;
  color: white;
  text-align: center;
}

#video-container h3 {
  font-family: "Cabin", "Open Sans", sans-serif;
  font-weight: bold;
  font-size: 2.5em;
  margin: 0.8rem 0 2.5rem 0;
}

#video-container h3 u {
  text-decoration: underline;
  text-decoration-color: #fb91445c;
}

#video-container a {
  text-decoration: none;
  color: white;
}

#video-container a svg {
  width: 60px;
}
</style>

<script>
export default {
  mounted() {},
};
</script>