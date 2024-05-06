<template>
  <BaseLayout>
    <div class="section-timeline-heading">
      <div class="container">
        <div class="padding-vertical-xlarge">
          <div class="timeline-main_heading-wrapper">
            <div class="margin-bottom-medium">
              <div class="timeline_date-text">Today</div>
            </div>
            <div class="margin-bottom-small">
              <div class="timeline_text">
                Today, I blend my tech skills and passion as a software
                engineer, adept in DevOps, cloud, and full-stack engineering. I
                nurture valuable connections and contribute to meaningful
                projects in the tech landscape.
              </div>
            </div>
            <div class="margin-bottom-large">
              <p class="paragraph-large">
                Explore my journey so far, and let's see how our paths can
                intersect.
              </p>
            </div>
            <a
              href="https://www.linkedin.com/in/r0a/"
              target="_blank"
              class="button-inverted w-button"
            >
              Connect with me
            </a>
          </div>
        </div>
      </div>
    </div>
  </BaseLayout>
</template>

<script>
import BaseLayout from "./BaseLayout.vue";

export default {
  name: "IndexPage",
  components: {
    BaseLayout,
  },
};
</script>

<style scoped>
@import "../../public/styles/timeline.css";
</style>
