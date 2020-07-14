<template>
  <div class="home">
    <img style="width: 70%;, display:block; , margin: 0 auto;, text-align: center;" alt="avator-marigotten" src="../assets/avator.jpg">
    <VerticalSlider/>
  </div>
</template>

<script>
// @ is an alias to /src
import VerticalSlider from '@/components/VerticalSlider.vue'

export default {
  name: 'Home',
  components: {
    VerticalSlider
    // HelloWorld
  }
}
</script>
