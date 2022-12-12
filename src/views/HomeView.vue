<template>
  <div class="home">
    <NavbarComponent />
    <HeaderComponent />
  </div>
</template>

<script>
// @ is an alias to /src
import NavbarComponent from '@/components/NavbarComponent.vue'
import HeaderComponent from '@/components/HeaderComponent.vue'

export default {
  name: 'HomeView',
  components: {
    NavbarComponent,
    HeaderComponent
  }
}
</script>
