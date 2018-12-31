<template>
  <div>
    <h1>{{name}}</h1>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: "Columbus!"
    };
  }
};
</script>

<style scoped>
h1 {
  color: green;
}
</style>