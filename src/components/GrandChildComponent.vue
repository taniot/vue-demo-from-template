<script>
export default {
  name: 'GrandChildComponent',
  props: {
    pluto: String,
  },
};
</script>

<template>
  <h2>Sono Grand Child COmponent</h2>

  <p>Sono il componente Grand Child Component</p>
  <p>Il testo che ricevo da Child Component è: {{ pluto }}</p>
</template>
