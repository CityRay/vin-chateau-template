<template>
  <HeadComponent />
  <RouterView />
  <FooterComponent />
</template>

<script>
import HeadComponent from '@/components/HeadComponent.vue';
import FooterComponent from '@/components/FooterComponent.vue';

export default {
  components: {
    HeadComponent,
    FooterComponent
  }
};
</script>

<style lang="scss">
@import "@/assets/scss/all.scss";
</style>
