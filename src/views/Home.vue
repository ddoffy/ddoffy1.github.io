<template>
  <sleep-calculator></sleep-calculator>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import SleepCalculator from "../components/SleepCalculator.vue";

export default defineComponent({
  name: "Home",

  components: {
    SleepCalculator,
  },
});
</script>
