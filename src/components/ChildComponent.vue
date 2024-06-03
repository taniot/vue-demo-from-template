<script>
import GrandChildComponent from './GrandChildComponent.vue';
import BrotherComponent from './BrotherComponent.vue';
import { store } from '../store';
export default {
  name: 'ChildComponent',
  components: {
    GrandChildComponent,
    BrotherComponent,
  },
  data() {
    return {
      store,
    };
  },
};
</script>

<template>
  <h2>Sono Child COmponent</h2>
  <p>Sono il componente Child Component</p>
  <p>{{ store.text }}</p>

  <GrandChildComponent />
  <BrotherComponent :text="store.text" />
</template>
