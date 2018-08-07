<template>
  <div class="review-response-box">
    <div class="row" v-bind:style="{marginTop: '2rem'}">
      <div class="col-1">
      image
      </div>
      <div class="col-10">
        <div class="review-info">

          <div class="review-send-info">
            <div class="sender">
              Sarah Moore
            </div>
            <div class="sent-at">
              Today
            </div>
          </div>

          <div class="rating">

          </div>
        </div>

        <div class="message" >
          There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable. If you are going to use a passage of Lorem Ipsum, you need to be sure there isn't anything embarrassing hidden in the middle of text.
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: "ReviewMessage",
    props: {
      msg: String
    }
  };
</script>

<style>
.review-response{
  padding-left: 1rem;
  padding-right: 1rem;
}

.review-response-menu .caret {
  float: left;
  width: 2%;
  line-height: 0.1rem;
  margin-top: -0.7rem;
}

.review-response-menu{
  border-bottom: 1px solid #93a6ba;
  height: 3rem;
  padding-top: 1rem;
}

.review-response-menu .social-site{
  margin-top: 2rem;
}

.review-send-info{
  width: 5rem;
  float: left;
}

.review-send-info .sender{
  font-size: 0.75rem;
  font-weight: bold;
  float: left
}
.review-send-info .sent-at{
  font-size: 0.6rem;
  float:left;
  /* font-weight: bold; */
}
.review-send-info .rating{
  float: right;
}
.review-info{
  width: 100%;
}
.message{
  margin-top: 5px;
  text-align: left;
  float: left;
  font-size: 0.7rem;
}

.review-response-box{
  border-bottom: 1px solid #93a6ba;
  padding-bottom: 20px;
}

</style>
