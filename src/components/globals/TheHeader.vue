<template>
  <b-navbar :mobile-burger="false" wrapper-class="container" type="is-primary">
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

<style scoped></style>
