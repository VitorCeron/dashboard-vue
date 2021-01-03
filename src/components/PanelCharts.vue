<template>
  <div class="mt-3">
    <b-card-group deck>
      <b-card bg-variant="light" header="Quantidade de vendas" class="text-center">
        <apexchart height="200" type="bar" :options="options" :series="series"></apexchart>
      </b-card>

      <b-card bg-variant="light" header="Valor total de vendas" class="text-center">
        <apexchart height="200" type="line" :options="options2" :series="series2"></apexchart>
      </b-card>
    </b-card-group>
    
  </div>
</template>

<script>
import VueApexCharts from 'vue-apexcharts';

export default {
  name: 'PanelCharts',
  data() {
    return {
      options: {
        xaxis: {
          categories: ['Mai', 'Jun', 'Jul', 'Ago', 'Set', 'Out', 'Nov', 'Dez']
        }
      },
      series: [{
        name: 'Total de vendas',
        data: [30, 40, 45, 50, 49, 60, 70, 150]
      }],
      options2: {
        xaxis: {
          categories: ['Mai', 'Jun', 'Jul', 'Ago', 'Set', 'Out', 'Nov', 'Dez']
        }
      },
      series2: [{
        name: 'Valor de vendas',
        data: [40000.00, 50000.00, 60000.00, 70000.00, 85000.00, 80000.00, 90000.00, 100256.98]
      }]
    }
  }
}
</script>

<style scoped>
</style>
