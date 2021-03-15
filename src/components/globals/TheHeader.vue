<template>
  <b-navbar :mobile-burger="false">
    <template #brand>
      <b-navbar-item tag="router-link" :to="{ path: '/' }">
        VueSample
      </b-navbar-item>
    </template>
  </b-navbar>
</template>

<script>
import Vue from "vue";

export default Vue.extend({});
</script>

<style scoped lang="scss"></style>
