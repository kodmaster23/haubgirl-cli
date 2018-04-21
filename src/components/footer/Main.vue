<template>
    <footer class="footer">
        <div class="container-fluid">
            <app-social-media></app-social-media>
            <app-contact></app-contact>
        </div>
    </footer>
</template>

<script>
    import SocialMedia from './SocialMedia.vue'
    import Contact from './Contact.vue'

    export default {
        name: "Footer",
        components:{
            'app-social-media': SocialMedia,
            'app-contact': Contact
        }
    }
</script>

<style scoped>



</style>