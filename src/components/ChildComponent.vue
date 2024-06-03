<script>
import GrandChildComponent from './GrandChildComponent.vue';
export default {
  name: 'ChildComponent',
  components: {
    GrandChildComponent,
  },
  props: ['pippo'],
};
</script>

<template>
  <h2>Sono Child COmponent</h2>
  <p>Sono il componente Child Component</p>

  <GrandChildComponent :pluto="pippo" />
</template>
