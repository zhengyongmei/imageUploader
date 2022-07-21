<template>
  <div class="home">
    <Uploader :img.sync="url" maxLimitWidth="1000" maxLimitHeight="1000" />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import Uploader from "@/components/Uploader.vue"; // @ is an alias to /src

@Component({
  components: {
    Uploader,
  },
})
export default class HomeView extends Vue {
  //http://pic1.win4000.com/wallpaper/2018-12-06/5c089769d3f02.jpg
  url = "http://pic1.win4000.com/wallpaper/2018-12-06/5c089769d3f02.jpg";
}
</script>
