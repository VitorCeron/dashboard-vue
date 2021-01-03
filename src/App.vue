<template>
  <div id="app">
    <Navbar />

    <Sidebar />

    <div class="container">
      <PanelCards />

      <PanelCharts />

      <PanelTable />
    </div>
  </div>
</template>

<script>
import Navbar from "@/components/Navbar";
import Sidebar from "@/components/Sidebar";
import PanelCards from "@/components/PanelCards";
import PanelCharts from "@/components/PanelCharts";
import PanelTable from "@/components/PanelTable";

export default {
  name: 'App',
  components: {
    Navbar,
    Sidebar,
    PanelCards,
    PanelCharts,
    PanelTable
  }
}
</script>

<style>
</style>
