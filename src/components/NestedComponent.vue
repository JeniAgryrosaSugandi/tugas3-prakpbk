<template>
    <div>
      <h2>Nested Component</h2>
      <button @click="emitData">Kirim Data ke Parent</button>
    </div>
  </template>
  
  <script>
  export default {
    methods: {
      emitData() {
        this.$emit('data-emitted', 'Data yang dikirim dari nested component');
      },
    },
  };
  </script>
  