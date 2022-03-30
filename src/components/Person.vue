<template>
  <div>
    <h1>Person</h1>
    <label for="name"
      >Nome| {{ person }} <br />
      <input type="text" v-model="name" placeholder="Insira seu nome" />
    </label>

    <hr />
    {{ name }}
  </div>
</template>

<script>
export default {
  // eslint-disable-next-line
  name: 'Person',
  data() {
    return {
      name: '',
      email: '',
      age: '',
      bio: '',
      isVisible: false,
    };
  },
};
</script>
