<template>
  <h1>{{ name }}</h1>
</template>
<script lang="ts">
import { defineComponent } from "vue";
export default defineComponent({
  setup() {
    const name = "keavvy";
    return {
      name,
    };
  },
});
</script>

