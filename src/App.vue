<template>
  <div id="app">
    <HeaderComponent />
    <MainComponent>
      <AdvertismentComponent />
      <ReviewsComponent />
      <ServiceComponent />
    </MainComponent>
    <FooterComponent />
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import MainComponent from './components/MainComponent.vue';
import AdvertismentComponent from './components/AdvertismentComponent.vue';
import ReviewsComponent from './components/ReviewsComponent.vue';
import ServiceComponent from './components/ServiceComponent.vue';
import FooterComponent from './components/FooterComponent.vue';

export default {
  components: {
    HeaderComponent,
    MainComponent,
    AdvertismentComponent,
    ReviewsComponent,
    ServiceComponent,
    FooterComponent
  }
};
</script>

<style src="@/styles/reset.css"></style>