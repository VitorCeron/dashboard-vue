<template>
  <div class="mt-3">
    <b-card-group class="card-group-dashboard" deck>
      <b-card bg-variant="primary" text-variant="white" header="Quantidade de produtos cadastrados" class="text-center">
        <b-card-text>10</b-card-text>
      </b-card>

      <b-card bg-variant="primary" text-variant="white" header="Quantidade de vendas" class="text-center">
        <b-card-text>150</b-card-text>
      </b-card>

      <b-card bg-variant="primary" text-variant="white" header="Valor total de vendas" class="text-center">
        <b-card-text>R$ 100.256,98</b-card-text>
      </b-card>
    </b-card-group>
  </div>
</template>

<script>
export default {
  name: 'Sidebar',
}
</script>

<style>
.card-group-dashboard > .card > .card-body {
  padding: 0.75rem;
}

.card-group-dashboard > .card > .card-body > .card-text {
  font-size: 35px;
}
</style>
