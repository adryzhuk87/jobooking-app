<template>
  <div class="application-view">
    <div class="info">
      <div class="left-side">
        <img class="jobooking-logo" :src="jobookingDarkBlueLogo" />
        <h1 class="heading">Hi, ich bin Lukas Mustermann.</h1>
        <p class="regular-text-1">
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et
          dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores. Lorem ipsum dolor
          sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna
          aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores.
        </p>
      </div>
      <div class="right-side"></div>
    </div>
  </div>
</template>

<script>
import jobookingDarkBlueLogo from '@/assets/images/jobooking-dark-blue-logo.png';
export default {
  setup() {
    return { jobookingDarkBlueLogo };
  },
};
</script>

<style scoped lang="scss">
// .application-view {}
.info {
  display: grid;
  grid-template-columns: 1fr 37.5%;
  .left-side {
    padding-top: 72px;
    padding-left: 128px;
    background-color: $color-interface-7;
  }
  .right-side {
    padding-top: 72px;
    padding-right: 128px;
    background-color: $color-interface-3;
  }
  .heading-1 {
    font-size: 64px;
    font-weight: 800;
    line-height: 72px;
    letter-spacing: 0.5px;
  }
  .jobooking-logo {
    width: 142px;
    margin-bottom: 43px;
  }
  .regular-text-1 {
    font-weight: 500;
    font-size: 16px;
    line-height: 26px;
  }
}
</style>
