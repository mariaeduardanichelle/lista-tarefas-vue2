<template>
  <header>
    <h1>{{ valor }}</h1>
  </header>
</template>

<script>
export default {
  props: ["valor"],
};
</script>

<style scoped>
header {
  background-color: grey;
  text-align-last: center;
  height: 60px;
  width: 100%;
  position: fixed;
  top: 0px;
}
</style>