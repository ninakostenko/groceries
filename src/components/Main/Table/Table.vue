<template>
  <div class="c-table">
    <Row v-for="category in categories" :category="category" />
  </div>
</template>

<script>
import './table.css'
import Row from './Row/Row.vue'
import groceries from '../../../constants/groceries.js'

export default {
  name: 'Table',
  components: {
    Row,
  },
  data() {
    return {
      categories: groceries,
    }
  },
}
</script>
