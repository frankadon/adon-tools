<template>
  <Header/>
  <div class="container">
    <h1>This is an about page</h1>
  </div>
</template>
<script>
// @ is an alias to /src
import Header from '@/components/Header.vue'

export default {
  name: 'About',
  components: {
    Header,
  }
}
</script>