<template>
  <div>
    <navbox></navbox>
    <footerbar></footerbar>
  </div>
</template>

<style lang="less">
</style>
<script>
import navbox from "./components/navbox.vue";
import footerbar from "@/views/footerbar";
export default {
  components: {
    navbox,
    footerbar
  }
};
</script>
