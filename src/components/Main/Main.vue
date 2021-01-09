<template>
  <div class="hed">
    <h1 class="c-row2"><u>Тестовая компания</u></h1>
    <h1>
      Комерческий отдел: <strong>Тел. 111111111</strong> <br />
      Тест Тест
    </h1>
    <h1>эл.почта: shop@gmail.com</h1>
    <h1 class="c-row3">Перечень товаров которые мы можем вам предложить: <br />цены мы готовы с Вами обсудить индивидуально</h1>
  </div>
  <Table />
</template>

<script>
import './main.css'
import Table from './Table/Table.vue'

export default {
  name: 'Main',
  components: {
    Table,
  },
}
</script>
