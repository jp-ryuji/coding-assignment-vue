<template>
  <div class="container">
    <b-table :data="users" :columns="columns"></b-table>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import titanic from "@/assets/titanic.json";

export default Vue.extend({
  name: "Home",
  data() {
    return {
      users: titanic,
      columns: [
        {
          field: "name",
          label: "Name"
        },
        {
          field: "sex",
          label: "Sex"
        },
        {
          field: "age",
          label: "Age"
        }
      ]
    };
  },
});
</script>
