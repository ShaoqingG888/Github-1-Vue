<script>
export default {
  data() {
    return {
      count: 0,
    };
  },
};
</script>
123
<template>
  <button @click="count++">Count is: {{ count }}</button>
</template>

<style scoped>
button {
  font-weight: bold;
}
</style>
