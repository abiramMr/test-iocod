<!-- eslint-disable vuejs-accessibility/form-control-has-label -->
<template lang="html">
  <PageHeader />
  <section class="home mt-5">
    <div class="container">
      <div class="text-block">
        <div class="first-text">
          <h1>
            We make great digital products for <br />
            <span>innovative</span> brands.
          </h1>
          <h6 class="mt-3">
            Get your desired design services from our talented designers, <br />
            around the world at a reasonable cost
          </h6>
        </div>
      </div>
      <div class="second-area">
        <div class="input-area me-4">
          <img src="@/assets/images/email.png" alt="email" class="mx-4" />
          <input type="email" placeholder="Your Work Email" />
        </div>
        <!-- <a href="#" class="btn">Book a call</a> -->
        <button class="btn">Book a call</button>
      </div>
      <div class="second-area mt-2">
        <img src="@/assets/images/Rating.png" alt="email" class="me-3" />
        <h6 class="mt-2">15+ Businesses, 35+ Happy clients.</h6>
      </div>
    </div>
  </section>
  <PageFooter/>
</template>

<script lang="js">
import PageHeader from '@/components/commons/Header.vue';
import PageFooter from '@/components/commons/Footer.vue';

export default {
  name: 'Home',
  props: [],
  components: {
    PageHeader,
    PageFooter,
  },
  setup() {
    return { };
  },
};
</script>

<style scoped lang="scss">
</style>
