<template>
  <div class="mt-3">
      <b-table striped hover :fields="fields" :items="items" bordered></b-table>
  </div>
</template>

<script>


export default {
  name: 'PanelTable',
  data() {
    return {
      fields: [
          {
            key: 'first_name',
            label: 'Nome'
          },
          {
            key: 'state',
            label: 'Estado'
          },
          {
            key: 'value',
            label: 'Valor'
          }
        ],
      items: [
          { first_name: 'Dickerson', state: 'SP', value: 'R$ 250,32' },
          { first_name: 'Larsen', state: 'RJ', value: 'R$ 250,32' },
          { first_name: 'Geneva', state: 'BA', value: 'R$ 250,32' },
          { first_name: 'Jami', state: 'MG', value: 'R$ 250,32' }
        ]
    }
  }
}
</script>

<style scoped>
</style>
