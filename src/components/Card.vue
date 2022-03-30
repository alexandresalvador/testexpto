<template>
  <div class="card">
    <h1>Card Componente</h1>
    <!-- <p>{{name}}</p>
<p>{{description}}</p> -->
    <p>{{ person }}</p>
  </div>
</template>

<script>
export default {
  name: 'CardProducts',
  props: {
    person: {
      type: Object,
      // required: true
    },
  },
  data() {
    return {
      //  name: 'Notebook',
      //   description: 'Core5, 2.6ghz, 8gb, tela whitescreen 15,4',
    };
  },
};
</script>
<style scoped>
.card {
  max-width: 400px;
  max-height: 200px;
  background-color: #eee;
  border: 1px solid #999;
  color: black;
  padding: 10px;
}
h1 {
  color: blue;
}
</style>
