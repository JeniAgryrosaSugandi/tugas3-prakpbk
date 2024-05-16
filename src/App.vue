<template>
  <div>
    <slot-component>
      <h2>Data atau Komponen yang Disisipkan</h2>
      <p>Ini adalah data atau komponen yang akan disisipkan.</p>
    </slot-component>
  </div>
</template>

<script>
import SlotComponent from './components/SlotComponent.vue';

export default {
  components: {
    SlotComponent,
  },
};
</script>
