<template>
  <div class="flex flex-col h-screen max-h-screen">
    <!-- search / results -->
    <div class="back flex justify-center relative px-4 pt-8 pb-32 "></div>
  </div>
  </template>

<script>
// @ is an alias to /src


export default {
  name: 'HomeView',
  components: {
  }
}
</script>

<style scoped>
.back{
background: radial-gradient(65% 100% at 50% 0%, #00FF94 0%, rgba(0, 255, 148, 0.25) 100%), linear-gradient(230deg, #000000 25%, #170059 100%), linear-gradient(215deg, #FFEBB9 10%, #19004E 80%), radial-gradient(100% 245% at 100% 100%, #FFFFFF 0%, #000353 100%), linear-gradient(125deg, #1400FF 0%, #3A0000 100%), linear-gradient(225deg, #00F0FF 30%, #000B6F 45%, #00EBFC 45%, #001676 65%, #00E1F6 65%, #001676 85%, #00ECFD 85%, #001676 100%), linear-gradient(135deg, #00F0FF 0%, #000B6F 15%, #00EBFC 15%, #001676 35%, #00E1F6 35%, #001676 55%, #00ECFD 55%, #001676 100%);
background-blend-mode: soft-light, screen, overlay, overlay, difference, overlay, normal;
}
</style>