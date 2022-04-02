<template>
<section>
 <HomePage/>
 <BackgroundImage/>
 <Services/>
</section>
 
</template>

<script>
import Header from '../components/HomePage.vue'
import BackgroundImage from '../components/BackgroundImage.vue'
import Services from '../components/Services.vue'

export default {
  components: { Header, BackgroundImage, Services},
  name: 'IndexPage'
}

</script>
