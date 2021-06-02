<template>
  <div class="about">
    <AboutUs msg="ABOUT ALL OF US" />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import AboutUs from "@/components/AboutUs.vue"; 

@Component({
  components: {
    AboutUs,
  },
})
export default class About extends Vue {}
</script>

<style scoped>

</style>
