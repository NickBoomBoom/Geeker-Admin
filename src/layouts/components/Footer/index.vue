<template>
  <div class="footer flx-center">
    <a href="javascript:void(0);" @click="open"> {{ PROJECT.footer }} </a>
  </div>
</template>
<script setup>
import { PROJECT } from "@/config";
function open() {
  if (PROJECT.footerUrl) {
    window.open(PROJECT.footerUrl, "_black");
  }
}
</script>
<style scoped lang="scss">
@import "./index.scss";
</style>
