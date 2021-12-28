<template>
  <div>
    <header-bar></header-bar>
    <b-container>
      <b-row class="mt-5">
        <router-view />
      </b-row>
    </b-container>
      <b-row>
      <data-table></data-table>
    </b-row>
  </div>
</template>

<script>
import HeaderBar from "@/components/HeaderBar.vue";
import DataTable from "@/components/DataTable.vue";


export default {
  components: {
    HeaderBar,
    DataTable,
  },
};
</script>