<template>
  <div class="review">
    <div class="card">
        <h1 v-bind:style="{color: '#2bb3ea', paddingTop: '2.7rem' }"> 4.5 </h1>
      <div class="card-body">
        <h6 v-bind:style="{color: '#2bb3ea'}"> 87 total reviews </h6>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Review",
  props: {
    msg: String
  }
};
</script>
