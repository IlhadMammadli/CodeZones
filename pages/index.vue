<template>
<section>
 <HomePage/>
 <BackgroundImage/>
</section>
 
</template>

<script>
import HomePage from '../components/HomePage.vue'
import BackgroundImage from '../components/BackgroundImage.vue'
export default {
  components: { HomePage, BackgroundImage},
  name: 'IndexPage'
}

</script>
