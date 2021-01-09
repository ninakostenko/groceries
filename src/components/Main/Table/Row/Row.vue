<template>
  <div class="c-row">
    <h1 class="c-title">{{ category.name }}</h1>

    <div class="c-item" v-for="item in category.items">
      <div class="c-item__name">
        <h4>{{ item.name }}</h4>
      </div>
      <div class="c-item__description">{{ item.description }}</div>
      <div class="c-item__price">
        <h2>{{ item.price + 'грн' }}/кг</h2>
      </div>
    </div>
  </div>
</template>

<script>
import './row.css'

export default {
  name: 'Row',
  props: {
    category: Object,
  },
}
</script>
