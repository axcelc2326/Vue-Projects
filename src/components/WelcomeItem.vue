<template>
  <div>
    <h1>Total Hero Price: {{ totalPrice }}BP</h1>
  </div>
</template>

<script>
export default {
  data() {
    return {
      items: [
        { Hero: 'Hylos', price: 32000 },
        { Hero: 'Beatrix', price: 32000 },
        { Hero: 'Lapu - Lapu', price: 32000 }
      ]
    };
  },

  
  computed: {
    // A computed property to calculate the total price of all items
    totalPrice() {
      return this.items.reduce((sum, item) => sum + item.price, 0);
    }
  }
};
</script>