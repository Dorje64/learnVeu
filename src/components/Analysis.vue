<template>
  <div class="analysis">
  asdf
    <Review/>
    df
  </div>
</template>

<script>
import Review from "./Review.vue";
export default {
  name: "Analysis",
  props: {
    msg: String
  },
  components: {
    Review
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
