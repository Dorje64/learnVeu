<template>
  <div class="about">
    <h1>This is an about pag</h1>
    <Analysis msg="Welcome to the Jungle"/>
  </div>
</template>

<script>
import Analysis from "@/components/Analysis.vue";

export default {
  name: "home",
  components: {
    Analysis
  }
};
</script>
