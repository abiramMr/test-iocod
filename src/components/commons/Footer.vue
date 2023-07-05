<template lang="html">
  <section class="mt-5">
    <footer>
      <div class="container">
        <div class="row">
          <div class="col-sm-4">
            <div class="card text-center">
              <div class="card-header"><img src="@/assets/images/Icon.png" alt="icon" /></div>
              <div class="card-body">
                <h3>Web Design</h3>
                <h6>
                  Crafting websites that convert and <br />
                  grow your business
                </h6>
              </div>
            </div>
          </div>
          <div class="col-sm-4">
            <div class="card text-center">
              <div class="card-header"><img src="@/assets/images/Icon_2.png" alt="icon" /></div>
              <div class="card-body">
                <h3>App Design</h3>
                <h6>Beautifully designed apps that your <br />users will love to use</h6>
              </div>
            </div>
          </div>
          <div class="col-sm-4">
            <div class="card text-center">
              <div class="card-header"><img src="@/assets/images/Icon_1.png" alt="icon" /></div>
              <div class="card-body">
                <h3>UX Audit</h3>
                <h6>
                  Get a detailed UX report on your <br />
                  marketing website
                </h6>
              </div>
            </div>
          </div>
        </div>
      </div>
    </footer>
  </section>
</template>

<script lang="js">
export default {
  name: 'Footers',
  props: [],
  setup() {
    return { };
  },
};
</script>

<style scoped lang="scss">
.footer {
}
</style>
