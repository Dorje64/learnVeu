 <template>
  <div class="home">
    <div class="container">
      <div class="row">
        <div class="col-8">
          <div class="row justify-content-around">
            <div class="col-6">
              <Review />
            </div>
            <div class="col-6">
              <Review />
            </div>
            <div class="col-6">
              <Launchpad />
            </div>
            <div class="col-6">
              <Review />
            </div>
            <div class="col-6">
              <Review />
            </div>
            <div class="col-6">
              <Review />
            </div>
          </div>
        </div>
        <div class="col-4">
          <ReviewMessage />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Analysis from "@/components/Analysis.vue";
import Review from "@/components/Review.vue";
import Launchpad from "@/components/launchpad.vue";
import ReviewMessage from "@/components/ReviewMessage"

export default {
  name: "home",
  components: {
    Analysis,
    Review,
    Launchpad,
    ReviewMessage
  }
};
</script>
