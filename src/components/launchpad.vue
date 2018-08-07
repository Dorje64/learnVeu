<template>
  <div class="launchpad">
    <div class= "card" v-bind:style="{ paddingTop: '3rem' }">
      <div class="row align-items-end">
        <div class="col-md-3"> </div>
          <div class="row d-flex justify-content-end">
       <div class="col">
          a
        </div>
        <div class="col">
          b
            <br />
            <span class="performance-way"> Invites </span>
        </div>
        <div class="col">
          c
            <br />
          <span class="performance-way"> Click Through </span>
        </div>
        <div class="col">
          d
        </div>
      </div>
      </div>
    </div>
  </div>

</template>

<script>
  export default {
    name: "Launchpad",
    props: {
      msg: String
    }
  };
</script>
