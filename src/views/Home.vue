<template>
  <div class="home">
    <Intro />
    <Fellowships />
    <Events />
    <Video />
    <Connect />
    <Verse />
  </div>
</template>

<style scoped>
.home {
  overflow: hidden;
}

.spacer-60 {
  margin: 60px;
}

.display-none {
  display: none;
}
</style>

<script>
import Intro from "@/components/Home/Intro.vue";
import Fellowships from "@/components/Home/Fellowships.vue";
import Events from "@/components/Home/Events.vue";
import Video from "@/components/Home/Video.vue";
import Connect from "@/components/Home/Connect.vue";
import Verse from "@/components/Home/Verse.vue";

export default {
  name: "Home",
  components: {
    Intro,
    Fellowships,
    Events,
    Video,
    Connect,
    Verse,
  },
};
</script>
