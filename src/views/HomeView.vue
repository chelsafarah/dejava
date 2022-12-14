<template>
  <div class="home">
    <NavbarComponent />
    <HeaderComponent />
    <StatisticContent />
  </div>
</template>

<script>
// @ is an alias to /src
import NavbarComponent from '@/components/NavbarComponent.vue'
import HeaderComponent from '@/components/HeaderComponent.vue'
import StatisticContent from '@/components/StatisticContent.vue';

export default {
  name: 'HomeView',
  components: {
    NavbarComponent,
    HeaderComponent,
    StatisticContent
  }
}
</script>

<style>
    .home {
        background-color: #FC9F9D;
    }
</style>
