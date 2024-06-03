<script>
export default {
  name: 'BrotherComponent',
  props: ['text'],
};
</script>
<template>
  <h2>Brother Component</h2>
  <p>Sono fratello di grand child</p>
  <p>{{ text }}</p>
</template>
