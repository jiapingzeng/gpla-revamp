<template>
  <div id="verse-container">
    <div class="verse-left">
      <h3>Why? We want to live out <br />these <u>verses</u></h3>
      <p>Any questions? Just ask!<br />We'd love to connect with you.</p>
      <a>Get connected</a>
    </div>
    <div class="verse-right">
      <img
        src="https://images.squarespace-cdn.com/content/v1/528d9e1ce4b04fc308327f74/1601503997404-S70IJVTGA9B8L0UB7AQD/ke17ZwdGBToddI8pDm48kKx_3i3bNR3GwJzi0t51IE1Zw-zPPgdn4jUwVcJE1ZvWQUxwkmyExglNqGp0IvTJZUJFbgE-7XRK3dMEBRBhUpx5bwldVRkVXHwvCX3RKUkOFabZSPJmB4YF8afAR1CZuGpOV9vSTR9vXXARlCTIw4Q/verse-tape.png"
      />
      <div class="verse-sticker">
        <h4>Acts 2:42-47</h4>
        <p>
          And they devoted themselves to the apostles' teaching and the
          fellowship, to the breaking of bread and the prayers. And awe came
          upon every soul, and many wonders and signs were being done through
          the apostles. And all who believed were together and had all things in
          common. And they were selling their possessions and belongings and
          distributing the proceeds to all, as any had need. And day by day,
          attending the temple together and breaking bread in their homes, they
          received their food with glad and generous hearts, praising God and
          having favor with all the people. And the Lord added to their number
          day by day those who were being saved.
        </p>
      </div>
    </div>
  </div>
</template>

<style scoped>
#verse-container {
  margin: auto;
  padding: 3em 0;
  position: relative;
  width: 100%;
  max-width: 1600px;
  height: 350px;
  background-color: #f4cf4c90;
  display: grid;
  grid-template-columns: repeat(2, 1fr);
}

#verse-container .verse-left {
  text-align: right;
  grid-column: span 1;
  margin: 2em 5em 1em 0;
}

#verse-container .verse-left h3 {
  font-family: "Cabin", "Open Sans", sans-serif;
  font-weight: bold;
  font-size: 2.5em;
  margin: 1rem 0 2rem 0;
}

#verse-container .verse-left h3 u {
  text-decoration: underline;
  text-decoration-color: #fb91445c;
}

#verse-container .verse-left p {
  color: white;
  font-family: "Cabin", "Open Sans", sans-serif;
  font-size: 1em;
  margin: 1.5em 0;
}

#verse-container .verse-left a {
  color: #f4cf4c90;
  font-family: "Cabin", "Open Sans", sans-serif;
  font-size: 1.3em;
  text-transform: uppercase;
  background-color: white;
  padding: 0.4em;
  margin: 1em 0;
  border-radius: 50px;
}

#verse-container .verse-right {
  grid-column: span 1;
  display: grid;
  place-items: center;
  position: relative;
}

.verse-right img {
  width: 150px;
  position: absolute;
  top: -10px;
  z-index: 3;
}

#verse-container .verse-right .verse-sticker {
  width: 85%;
  background-color: white;
  box-shadow: -3px 3px 2px #00000030;
  transform: rotate(3deg);
  text-align: center;
  margin: 1rem 0 0 0;
}

.verse-sticker h4 {
  font-size: 2.6em;
  font-family: "Cabin", "Open Sans", sans-serif;
  text-transform: uppercase;
  margin: 0;
  padding: 1em 0 0 0;
}

.verse-sticker p {
  font-family: "Cabin", "Open Sans", sans-serif;
  padding: 1rem 2rem 2rem 2rem;
  font-size: 0.8em;
  font-style: italic;
}
</style>

<script>
export default {
  name: "Verse",
};
</script>