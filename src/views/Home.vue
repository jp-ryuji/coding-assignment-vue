<template>
  <div class="container my-5">
    <user-search-form></user-search-form>
    <b-table :data="users" :columns="columns"></b-table>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import titanic from "@/assets/titanic.json";
import UserSearchForm from "@/components/parts/UserSearchForm.vue";

export default Vue.extend({
  components: { UserSearchForm },
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
  }
});
</script>
