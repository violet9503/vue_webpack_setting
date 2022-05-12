<template>
  <h1>{{ msg }}</h1>
  <Hello></Hello>
</template>

<script>
import Hello from "~/components/Hello";

export default {
  components: {
    Hello,
  },
  data() {
    return {
      msg: "hello af",
    };
  },
};
</script>
<style>
h1 {
  color: orange;
}
</style>
