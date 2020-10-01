<template>
  <div class="about">
    <Intro />
    <div class="spacer-60"></div>
    <Story />
    <Church />
    <Pastor />
    <Connect />
  </div>
</template>

<style>
@import url("https://fonts.googleapis.com/css?family=Cabin");
@import url("https://fonts.googleapis.com/css?family=Open+Sans");

.about {
  overflow: hidden;
}

.spacer-60 {
  margin: 60px;
}
</style>

<script>
import Intro from "@/components/About/Intro.vue";
import Story from "@/components/About/Story.vue";
import Church from "@/components/About/Church.vue";
import Pastor from "@/components/About/Pastor.vue";
import Connect from "@/components/About/Connect.vue";

export default {
  name: "About",
  components: {
    Intro,
    Story,
    Church,
    Pastor,
    Connect,
  },
  mounted() {
    window.onresize = () => location.reload();
  },
};
</script>