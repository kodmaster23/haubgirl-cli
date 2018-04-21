<template>
    <div id="home">
        <app-header></app-header>
        <app-resume></app-resume>
        <!--<app-gallery></app-gallery>-->
        <!--<app-video-prev></app-video-prev>-->
        <!--<app-shop></app-shop>-->
        <!--<app-footer></app-footer>-->
    </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/header/Main.vue'
import Resume from '@/components/body/Resume.vue'
import Gallery from '@/components/body/Gallery.vue'
import VideoPreview from '@/components/body/VideoPreview.vue'
import Shop from '@/components/body/Shop.vue'
import Footer from '@/components/footer/Main.vue'

export default {
  name: 'home',
  components: {
    'app-header': Header,
    'app-resume': Resume,
    'app-gallery': Gallery,
    'app-video-prev': VideoPreview,
    'app-shop': Shop,
    'app-footer': Footer
  }
}
</script>

<style>

</style>