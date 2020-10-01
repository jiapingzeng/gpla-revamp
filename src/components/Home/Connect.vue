<template>
  <div class="connect-container">
    <div class="connect-album-container">
      <div class="connect-text-container-left">
        <h3>
          But we do more than just
          <br />
          <b>meet on Sundays</b>
        </h3>
      </div>
      <div class="connect-album">
        <div class="connect-album-left">
          <img src="https://images.squarespace-cdn.com/content/v1/528d9e1ce4b04fc308327f74/1595543103026-BONFAOU461LRRWYI9GMT/ke17ZwdGBToddI8pDm48kPwMUiRewZl3P4I6VEKGsYFZw-zPPgdn4jUwVcJE1ZvWQUxwkmyExglNqGp0IvTJZamWLI2zvYWH8K3-s_4yszcp2ryTI0HqTOaaUohrI8PIrfcuZDCacDHhWEz1r3OCbKAcUQJzS4xYT2Manfo8kyM/connect1.png" />
          <img src="https://images.squarespace-cdn.com/content/v1/528d9e1ce4b04fc308327f74/1595543102572-0D53NK4M3NBY0DRD5W6H/ke17ZwdGBToddI8pDm48kN0Ab-Vm-yW6YhPYVRk5ALJZw-zPPgdn4jUwVcJE1ZvWQUxwkmyExglNqGp0IvTJZamWLI2zvYWH8K3-s_4yszcp2ryTI0HqTOaaUohrI8PImJHNUALCZ-xpnEYojNI03JyvxnCU5geDl1eXn8ZySmM/connect2.png" />
          <p>We join together for Thanksgiving retreats, winter retreats, inter-church collaboratives, missions trips and plan for events together.</p>
        </div>
        <div class="connect-album-right">
          <img src="https://images.squarespace-cdn.com/content/v1/528d9e1ce4b04fc308327f74/1595543105811-B5ULTKEXOPDT31WHIL5Y/ke17ZwdGBToddI8pDm48kMLXQEsKct3rCkzlZGgLrkpZw-zPPgdn4jUwVcJE1ZvWQUxwkmyExglNqGp0IvTJZamWLI2zvYWH8K3-s_4yszcp2ryTI0HqTOaaUohrI8PIvlJlJN5Ir2DgBP-dmLuLl9TzkeWR5gsCeHyw2jWLzWI/connect3.png" />
          <img src="https://images.squarespace-cdn.com/content/v1/528d9e1ce4b04fc308327f74/1595543106023-TQAL5R6QKZ19UVUBXYF0/ke17ZwdGBToddI8pDm48kBli0KgB-bdbMaf_mh9xvF1Zw-zPPgdn4jUwVcJE1ZvWQUxwkmyExglNqGp0IvTJZamWLI2zvYWH8K3-s_4yszcp2ryTI0HqTOaaUohrI8PIk7iYaA6YmCY9HN_gG_r_TgNtMd-nDKcmkndvjJW8EKM/connect4.png" />
          <p>But most importantly, we just do life together. Go on trips, celetebrate birthdays, study for exams together.</p>
        </div>
      </div>
      <div class="connect-text-container-right">
        <h3>
          <b>Like family</b>
        </h3>
      </div>
    </div>
    <div class="get-connected">
      <div class="get-connected-image-container">
        <img src="https://images.squarespace-cdn.com/content/v1/528d9e1ce4b04fc308327f74/1595543106845-2AWKB067MLK5F8S5ODIC/ke17ZwdGBToddI8pDm48kGgDth4Lzn7OmOqKPQZDfUV7gQa3H78H3Y0txjaiv_0fDoOvxcdMmMKkDsyUqMSsMWxHk725yiiHCCLfrh8O1z5QPOohDIaIeljMHgDF5CVlOqpeNLcJ80NK65_fV7S1USgnp6t6_BjKPgWQi0Zb7zFSBz4TUcQwbKcog3qJm_bgm4bjm9DAHF2kOsIZRJKXnA/get-connected.png" />
        <img
          src="https://images.squarespace-cdn.com/content/v1/528d9e1ce4b04fc308327f74/1594080670766-RE0GX152ZA9ZT597QMZE/ke17ZwdGBToddI8pDm48kM-OpN-va16xooL4OSPj4SpZw-zPPgdn4jUwVcJE1ZvWEtT5uBSRWt4vQZAgTJucoTqqXjS3CfNDSuuf31e0tVHsMHB5B1FdADP7yL6VWXJXMKJvdVEjXW_IRLNphPOKaW0nsU3dfn6w--du8-EjPUE/pngguru+1.png"
        />
      </div>
      <div class="get-connected-text">
        <h3>
          <a href="#">
            Find out more about
            <br />our small groups and
            <br />fellowships here!
          </a>
        </h3>
      </div>
    </div>
  </div>
</template>

<style scoped>
.connect-container {
  width: 100%;
  max-width: 1500px;
  margin: auto;
}

.connect-container h3 {
  color: #3c3c3c;
  font-family: "Permanent Marker", "Cabin", "Open Sans", sans-serif !important;
  font-size: 25px;
  font-weight: normal;
  text-align: right;
  display: inline-block;
}

.connect-container h3 b {
  font-weight: normal;
  font-size: 30px;
}

.connect-container a {
  color: inherit;
  text-decoration: none;
}

.connect-container .connect-album-container h3:first-child {
  margin-left: 2em;
  text-align: right;
}

.connect-container .connect-album-container h3:last-child {
  text-align: right;
}

.connect-album {
  display: grid;
  grid-template-columns: 50% 50%;
  height: 400px;
}

.connect-album-left {
  position: relative;
}

.connect-album-left img:first-child {
  position: absolute;
  top: 0px;
  left: 50px;
  z-index: 1;
}

.connect-album-left img:nth-child(2) {
  position: absolute;
  top: 170px;
  left: 90px;
  z-index: 2;
}

.connect-album-left p {
  position: absolute;
  width: 200px;
  top: 50px;
  left: 320px;
  background-color: #f4cf4ccc;
  font-family: "Cabin", "Open Sans", sans-serif;
  padding: 65px 50px 65px 100px;
  z-index: 0;
}

.connect-album-left {
  width: 350px;
}

.connect-album-right {
  position: relative;
}

.connect-album-right img:first-child {
  position: absolute;
  top: 0px;
  left: 40px;
  z-index: 2;
}

.connect-album-right img:nth-child(2) {
  position: absolute;
  top: 150px;
  left: 100px;
  z-index: 1;
}

.connect-album-right p {
  position: absolute;
  width: 200px;
  top: 50px;
  left: 330px;
  background-color: #f4cf4ccc;
  font-family: "Cabin", "Open Sans", sans-serif;
  padding: 65px 50px 65px 100px;
  z-index: 0;
}

.connect-album img {
  width: 300px;
  border-radius: 10px;
}

.connect-text-container-left {
  display: flex;
  justify-content: flex-start;
  margin: 30px 40px;
}

.connect-text-container-right {
  display: flex;
  justify-content: flex-end;
  margin: 30px 60px;
}

.connect-container .get-connected h3 {
  text-align: left;
}

.get-connected {
  display: flex;
  align-items: center;
  justify-content: center;
}

.get-connected-image-container img:first-child {
  width: 600px;
}

.get-connected-image-container img:last-child {
  width: 300px;
  margin-left: -100px;
  margin-bottom: -30px;
}

.get-connected-text {
  margin-top: 100px;
}
</style>

<script>
export default {
  name: "Connect",
};
</script>