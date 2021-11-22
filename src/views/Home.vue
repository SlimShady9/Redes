<script>
import IntroContent from '@/components/IntroContent.vue'
import Footer from '@/components/Footer.vue'
import Content from '@/components/Content.vue'

export default {
    components: {
        IntroContent,
        Footer,
        Content,
    },
}
</script>

<template>
  <div class="to-amber-100 from-red-400 bg-gradient-to-b">
    <IntroContent />
    <Content/>
    <Footer />
  </div>
  
</template>
