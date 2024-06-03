<script>
import { store } from '../store';
export default {
  name: 'GrandChildComponent',
  data() {
    return {
      store,
    };
  },
};
</script>

<template>
  <h2>Sono Grand Child COmponent</h2>

  <p>Sono il componente Grand Child Component</p>

  <hr />
  <div>
    <label for="store-text">Modifica il contenuto dello store</label>
  </div>
  <div>
    <input type="text" v-model="store.text" />
  </div>
</template>
