<template>
  <div class="flex flex-col h-screen max-h-screen">
    <!-- search / results -->
    <div class="back flex justify-center relative px-4 pt-8 pb-32">
      <!-- search input -->
      <div class="w-full max-w-screen-sm">
        <h1 class="text-center text-white text-4xl font-bold pb-8">
          IP Adress Tracker
        </h1>
        <div class="flex">
          <input
            type="text"
            placeholder="Search for any IP address or leave it empty to your IP info"
            class="flex-1 py-3 px-2 rounded-tl-md rounded-bl-md focus:outline-none"
          />
          <i
            class="fas fa-chevron-right cursor-pointer bg-black text-white px-4 rounded-tr-md rounded-br-md flex items-center"
          ></i>
        </div>
      </div>
      <!-- ip information box -->
      <IPInfo />
    </div>
    
  </div>
</template>

<script>
// @ is an alias to /src
import IPInfo from '@/components/IPInfo.vue'
export default {
  name: "HomeView",
  components: {
    IPInfo
  },
};
</script>

<style scoped>
.back {
  background: radial-gradient(
      65% 100% at 50% 0%,
      #00ff94 0%,
      rgba(0, 255, 148, 0.25) 100%
    ),
    linear-gradient(230deg, #000000 25%, #170059 100%),
    linear-gradient(215deg, #ffebb9 10%, #19004e 80%),
    radial-gradient(100% 245% at 100% 100%, #ffffff 0%, #000353 100%),
    linear-gradient(125deg, #1400ff 0%, #3a0000 100%),
    linear-gradient(
      225deg,
      #00f0ff 30%,
      #000b6f 45%,
      #00ebfc 45%,
      #001676 65%,
      #00e1f6 65%,
      #001676 85%,
      #00ecfd 85%,
      #001676 100%
    ),
    linear-gradient(
      135deg,
      #00f0ff 0%,
      #000b6f 15%,
      #00ebfc 15%,
      #001676 35%,
      #00e1f6 35%,
      #001676 55%,
      #00ecfd 55%,
      #001676 100%
    );
  background-blend-mode: soft-light, screen, overlay, overlay, difference,
    overlay, normal;
}
</style>
