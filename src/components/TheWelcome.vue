<template>
  <h1>
    <ol>
      <li v-for="(item, index) in items" :key="index">
        Name : {{ item.hero }}    ->    Role : {{ item.role }}
      </li>
    </ol>
  </h1>
</template>

<script>
export default {
  data() {
    return {
      items: [
        { hero: 'Hylos', role: 'Tank' },
        { hero: 'Beatrix', role: 'Marksman' },
        { hero: 'Lapu - Lapu', role: 'Fighter' }
      ]
    };
  }
};
</script>