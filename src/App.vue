<template>
  <div>
    <h1>Welcome here.</h1>
    <div>Hello {{ value }}</div>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      value: "World"
    };
  }
};
</script>
