<template>
  <div id="app">
    <TheHeader />
    <router-view />
  </div>
</template>

<script>
import TheHeader from "@/components/globals/TheHeader.vue";
import Vue from "vue";

export default Vue.extend({
  components: { TheHeader }
});
</script>
