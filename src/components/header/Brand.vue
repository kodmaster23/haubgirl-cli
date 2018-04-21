<template>
    <div class="navbar-header">
        <router-link class="navbar-brand" to="/">{{brand}}</router-link>
    </div>
</template>

<script>
    export default {
        name: "Brand",
        data () {
            return {
                brand: 'NMS'
            }
        },
        methods : {
            toggle () {
                this.$emit('toggle')
            }
        }
    }
</script>

<style scoped>

</style>