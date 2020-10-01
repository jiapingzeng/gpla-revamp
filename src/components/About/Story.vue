<template>
  <div class="story-container">
    <div class="story-canvas-container">
      <canvas id="story-dotted-background"></canvas>
    </div>
    <div class="story-text-container">
      <h2>
        we all have a
        <u>story</u>
      </h2>
      <h4>And now we're part of God's story.</h4>
    </div>
    <div class="story-image-container">
      <div class="story-arrow">
        <!-- SVG from Font awesome https://fontawesome.com/ -->
        <svg
          aria-hidden="true"
          focusable="false"
          data-prefix="fas"
          data-icon="chevron-right"
          class="svg-inline--fa fa-chevron-right fa-w-10"
          role="img"
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 320 512"
          style="transform: rotate(180deg)"
        >
          <path
            fill="currentColor"
            d="M285.476 272.971L91.132 467.314c-9.373 9.373-24.569 9.373-33.941 0l-22.667-22.667c-9.357-9.357-9.375-24.522-.04-33.901L188.505 256 34.484 101.255c-9.335-9.379-9.317-24.544.04-33.901l22.667-22.667c9.373-9.373 24.569-9.373 33.941 0L285.475 239.03c9.373 9.372 9.373 24.568.001 33.941z"
          />
        </svg>
      </div>
      <div class="story-block" id="story1">
        <div class="story-block-text">
          <h4>Christine</h4>
          <h5>CO2017</h5>
        </div>
        <div class="story-block-image">
          <img
            src="https://images.squarespace-cdn.com/content/v1/528d9e1ce4b04fc308327f74/1594871630661-EF9QW2HJ5KGWTR1FIZRG/ke17ZwdGBToddI8pDm48kIYsg0DehWavQP-0f8yLXx97gQa3H78H3Y0txjaiv_0fDoOvxcdMmMKkDsyUqMSsMWxHk725yiiHCCLfrh8O1z5QHyNOqBUUEtDDsRWrJLTmGyshuIVypohjMxDyn913REE588txBSZwFt6X7LirZu9TWejOGToZbAbjVWJlxpHi/story-image1.png"
          />
        </div>
      </div>
      <div class="story-block" id="story2">
        <div class="story-block-text">
          <h4>Andrew &amp; Winston</h4>
          <h5>Seniors</h5>
        </div>
        <div class="story-block-image">
          <img
            src="https://images.squarespace-cdn.com/content/v1/528d9e1ce4b04fc308327f74/1594871631570-O8GBV4T91429QWXAZWAW/ke17ZwdGBToddI8pDm48kFh8Oin-lmQjX3qjQ5VL_5V7gQa3H78H3Y0txjaiv_0fDoOvxcdMmMKkDsyUqMSsMWxHk725yiiHCCLfrh8O1z5QPOohDIaIeljMHgDF5CVlOqpeNLcJ80NK65_fV7S1UVykr5RkOzX9Q3jqnTqRaQwZrkKOC_v7AJ_QjebvvmVuP7cJNZlDXbgJNE9ef52e8w/story-image2.png"
          />
        </div>
      </div>
      <div class="story-block" id="story3">
        <div class="story-block-text">
          <h4>Nadia</h4>
          <h5>Senior</h5>
        </div>
        <div class="story-block-image">
          <img
            src="https://images.squarespace-cdn.com/content/v1/528d9e1ce4b04fc308327f74/1599085378926-WDTPCB64JQGD22IWHPL6/ke17ZwdGBToddI8pDm48kKUg5ZB7JzP6kAkO7BGdxXcUqsxRUqqbr1mOJYKfIPR7LoDQ9mXPOjoJoqy81S2I8GRo6ASst2s6pLvNAu_PZdK_u6wtnoSd8KPxYFr3_aLM41cvi4msafVSJH1Gd2Mv36tkeQm9Ei0J2zx3JxEJTdY/story-image3.png"
          />
        </div>
      </div>
      <div class="story-arrow">
        <!-- SVG from Font awesome https://fontawesome.com/ -->
        <svg
          aria-hidden="true"
          focusable="false"
          data-prefix="fas"
          data-icon="chevron-right"
          class="svg-inline--fa fa-chevron-right fa-w-10"
          role="img"
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 320 512"
        >
          <path
            fill="currentColor"
            d="M285.476 272.971L91.132 467.314c-9.373 9.373-24.569 9.373-33.941 0l-22.667-22.667c-9.357-9.357-9.375-24.522-.04-33.901L188.505 256 34.484 101.255c-9.335-9.379-9.317-24.544.04-33.901l22.667-22.667c9.373-9.373 24.569-9.373 33.941 0L285.475 239.03c9.373 9.372 9.373 24.568.001 33.941z"
          />
        </svg>
      </div>
    </div>
    <div class="story-lightbox" id="story-lightbox">
      <div class="story-lightbox-content">
        <div class="story-content-container">
          <div class="story-content" id="story1-content">
            <div class="story-content-image">
              <img
                src="https://images.squarespace-cdn.com/content/v1/528d9e1ce4b04fc308327f74/1601486042923-MF0YGLQEFWV74VJIK7JJ/ke17ZwdGBToddI8pDm48kF6hVDwN1OkscBVecokTACwUqsxRUqqbr1mOJYKfIPR7LoDQ9mXPOjoJoqy81S2I8N_N4V1vUb5AoIIIbLZhVYxCRW4BPu10St3TBAUQYVKcm2zuQDSXVLwVE8Vttaf6dCI8n5xcFF92hQ8pnXLCsPJVDGS8r3gFm6Czye2u18BS/story-slide1-1.png"
              />
              <img
                src="https://images.squarespace-cdn.com/content/v1/528d9e1ce4b04fc308327f74/1601486277139-V3IYJMZUD8LQ8HP1NDT2/ke17ZwdGBToddI8pDm48kD431tEcx6G1QaO-BosivwUUqsxRUqqbr1mOJYKfIPR7LoDQ9mXPOjoJoqy81S2I8N_N4V1vUb5AoIIIbLZhVYxCRW4BPu10St3TBAUQYVKcnTnu7XBlj1VpkGNaFFmAGQfiEvSBt3CpPcsT4TszsEg3_BY7w1VxLjvHZvkW0xFb/story-slide1-2.png"
              />
              <h3>lost</h3>
              <h3>found</h3>
            </div>
            <div class="story-content-text">
              <h4>Christine</h4>
              <h5><i>CO2017, boba enthusiast</i></h5>
              <h5>
                " I was so lost to myself,
                <br />but now in Jesus, I'm found.
              </h5>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
                enim ad minim veniam, quis nostrud exercitation ullamco laboris
                nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor
                in reprehenderit in voluptate velit esse cillum dolore eu fugiat
                nulla pariatur.
              </p>
            </div>
          </div>
          <div class="story-content" id="story2-content">
            <div class="story-content-image"></div>
            <div class="story-content-text">
              <p>Winston &amp; Andrew</p>
            </div>
          </div>
          <div class="story-content" id="story3-content">
            <div class="story-content-image"></div>
            <div class="story-content-text">
              <p>Nadia</p>
            </div>
          </div>
        </div>
        <div id="lightbox-close">
          <!-- SVG from Font awesome -->
          <svg
            aria-hidden="true"
            focusable="false"
            data-prefix="fas"
            data-icon="times"
            class="svg-inline--fa fa-times fa-w-11"
            role="img"
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 352 512"
          >
            <path
              fill="currentColor"
              d="M242.72 256l100.07-100.07c12.28-12.28 12.28-32.19 0-44.48l-22.24-22.24c-12.28-12.28-32.19-12.28-44.48 0L176 189.28 75.93 89.21c-12.28-12.28-32.19-12.28-44.48 0L9.21 111.45c-12.28 12.28-12.28 32.19 0 44.48L109.28 256 9.21 356.07c-12.28 12.28-12.28 32.19 0 44.48l22.24 22.24c12.28 12.28 32.2 12.28 44.48 0L176 322.72l100.07 100.07c12.28 12.28 32.2 12.28 44.48 0l22.24-22.24c12.28-12.28 12.28-32.19 0-44.48L242.72 256z"
            />
          </svg>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.story-container {
  margin: auto;
  width: 100%;
  max-width: 1600px;
  height: 750px;
  display: grid;
  position: relative;
  grid-template-rows: 30% 65%;
}

.story-canvas-container {
  position: absolute;
  width: 100%;
  height: inherit;
  z-index: 0;
}

.story-text-container {
  margin: 2em 8em 1em 0;
  text-align: right;
  white-space: nowrap;
  z-index: 1;
}

.story-text-container h2 {
  text-transform: none;
  font-family: "Cabin", "Open Sans", sans-serif !important;
  -webkit-text-fill-color: transparent;
  -webkit-text-stroke: 2px #f4cf4c;
  font-size: 4.5em;
  font-style: normal;
  font-weight: normal;
  margin: 0px;
  letter-spacing: normal !important;
}

.story-text-container h2 u {
  -webkit-text-fill-color: #f4cf4c;
  -webkit-text-stroke: 2px #f4cf4c;
  text-decoration: underline;
  text-decoration-color: #fb91445c;
  font-weight: bold;
}

.story-text-container h4 {
  font-family: "Cabin", "Open Sans", sans-serif !important;
  font-size: 1.8em;
  font-weight: bold;
  line-height: 1em;
  margin: 1em 0;
}

.story-image-container {
  width: 100%;
  height: 100%;
  z-index: 1;
  display: grid;
  grid-template-columns: 5% 27.5% 40% 17.5% 5%;
  grid-gap: 1.25%;
}

.story-image-container .story-arrow {
  display: grid;
  place-items: center;
  padding: 20%;
  color: rgba(244, 207, 76, 0.6);
}

.story-image-container .story-block {
  position: relative;
  cursor: pointer;
}

.story-block .story-block-text {
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 80%;
  border-radius: 20px;
  background-color: rgba(244, 207, 76, 0.6);
}

.story-block .story-block-text h4 {
  font-family: "Cabin", "Open Sans", sans-serif !important;
  font-weight: normal !important;
  color: white;
  font-size: 2.5em;
  margin: 20px 0 0 20px;
}

.story-block .story-block-text h5 {
  font-family: "Cabin", "Open Sans", sans-serif !important;
  font-weight: normal !important;
  font-style: italic;
  color: white;
  font-size: 1.7em;
  margin: 0 0 0 20px;
}

.story-block .story-block-image {
  position: absolute;
  right: 0;
  bottom: 0;
  height: 85%;
  overflow: hidden;
}

.story-block .story-block-image img {
  height: 100%;
}

.story-lightbox {
  background-color: rgba(0, 0, 0, 0.6);
  position: absolute;
  width: 100%;
  height: 100%;
  z-index: 10;
  display: grid;
  place-items: center;
}

.story-lightbox .story-lightbox-content {
  background-color: white;
  width: 90%;
  height: 65%;
  border-radius: 10px;
  display: grid;
  grid-template-columns: 95% 5%;
}

.story-lightbox .story-content {
  display: none;
  grid-template-columns: 50% 50%;
  height: 100%;
  text-align: right;
}

.story-lightbox .story-content .story-content-text {
  margin: 2em 0 0 2em;
}

.story-lightbox #lightbox-close {
  cursor: pointer;
  text-align: center;
}

.story-lightbox #lightbox-close svg {
  margin-top: 1em;
  color: darkgrey;
  width: 30%;
}

.story-content-image {
  position: relative;
  margin: 2em 0 2em 2em;
}

.story-content-image img {
  position: absolute;
  width: 55%;
}

#story1-content .story-content-image img:first-of-type {
  top: 0;
  left: 0;
}

#story1-content .story-content-image img:last-of-type {
  right: 0;
  bottom: 0;
}

#story1-content .story-content-image h3 {
  font-family: "Cabin", "Open Sans", sans-serif !important;
  font-size: 5.5em;
  margin: 2.2rem 0;
  color: #f4cf4c;
}

#story1-content .story-content-image h3:first-of-type {
  position: absolute;
  top: 0;
  right: 0;
  text-align: right;
  font-family: "Cabin", "Open Sans", sans-serif !important;
  -webkit-text-fill-color: transparent;
  -webkit-text-stroke: 1px #f4cf4c;
}

#story1-content .story-content-image h3:last-of-type {
  position: absolute;
  bottom: 0;
  left: 0;
  text-align: left;
}

#story1-content .story-content-image h4 {
  font-size: 5em;
}

.story-content-text h4 {
  font-family: "Cabin", "Open Sans", sans-serif !important;
  font-weight: bold;
  font-size: 4em;
  margin: 0 0 0 0;
}

.story-content-text h5 {
  font-family: "Cabin", "Open Sans", sans-serif !important;
  font-weight: normal !important;
  color: #f4cf4c;
  font-size: 1.8em;
  margin: 0 0 0.8em 0;
}

.story-content-text h5 i {
  font-family: "Cabin", "Open Sans", sans-serif !important;
  font-weight: normal !important;
  color: black;
}

.story-content-text p {
  font-family: "Cabin", "Open Sans", sans-serif !important;
  font-weight: normal !important;
  font-size: 1.3em;
  margin: 0 0 0.5em 0;
}
</style>

<script>
export default {
  name: "Story",
  mounted() {
    // draw dotted backgrounds
    const c2 = document.getElementById("story-dotted-background");
    const cs2 = getComputedStyle(c2.parentElement);
    const ctx2 = c2.getContext("2d");
    const c2width = parseInt(cs2.width);
    const c2height = parseInt(cs2.height);

    c2.width = c2width;
    c2.height = c2height;

    ctx2.setLineDash([0.5, 6]);
    ctx2.beginPath();
    for (let i = 0; i < c2height; i += 6) {
      ctx2.moveTo((i % 12) / 2, i);
      ctx2.lineTo(c2width, i);
    }
    ctx2.stroke();

    // story lightbox
    const lightbox = document.getElementById("story-lightbox");
    const storyIds = ["story1", "story2", "story3"];
    const lightboxClose = document.getElementById("lightbox-close");

    lightbox.style.display = "none";
    storyIds.map((id) => {
      document.getElementById(id).onclick = () => {
        lightbox.style.display = "grid";
        document.getElementById(`${id}-content`).style.display = "grid";
      };
    });
    lightboxClose.onclick = () => {
      lightbox.style.display = "none";
      storyIds.map((id) => {
        document.getElementById(`${id}-content`).style.display = "none";
      });
    };
  },
};
</script>