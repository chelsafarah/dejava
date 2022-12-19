<template>
  <div class="home">
    <NavbarComponent />
    <HeaderComponent />
    <StatisticContent />
    <TestimonialContent />
    <FooterComponent />
  </div>
</template>

<script>
// @ is an alias to /src
import NavbarComponent from '@/components/NavbarComponent.vue'
import HeaderComponent from '@/components/HeaderComponent.vue'
import StatisticContent from '@/components/StatisticContent.vue';
import TestimonialContent from '@/components/TestimonialContent.vue';
import FooterComponent from '@/components/FooterComponent.vue';

export default {
  name: 'HomeView',
  components: {
    NavbarComponent,
    HeaderComponent,
    StatisticContent,
    TestimonialContent,
    FooterComponent
  }
}
</script>

<style>
    .home {
        background-color: #FC9F9D;
    }
</style>
