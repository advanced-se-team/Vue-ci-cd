<template>
  <div>
    <h1>{{ greeting }}</h1>
  </div>
</template>

<script>
export default {
  data() {
    return {
      greeting: 'Hello, Vue!'
    };
  }
};
</script>

<style scoped>
h1 {
  color: green;
}
</style>
