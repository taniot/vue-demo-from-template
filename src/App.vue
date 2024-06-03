<script>
import ChildComponent from './components/ChildComponent.vue';

export default {
  components: {
    ChildComponent,
  },
  data() {
    return {
      text: 'testo definito in APP',
    };
  },
};
</script>

<template>
  <h1>Demo from Vue Template</h1>
  <p>Testo di demo per font</p>

  <ChildComponent :pippo="text" demo="testo qui dichiarato" />
</template>
<!-- <style></style> -->
