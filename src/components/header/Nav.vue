<template>
       <b-navbar toggleable="md" type="light" fixed="top" variant="light">

        <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>

        <b-navbar-brand href="#">NavBar</b-navbar-brand>

        <b-collapse is-nav id="nav_collapse">

            <b-navbar-nav class="ml-auto">
                <b-nav-item href="#">Link</b-nav-item>
                <b-nav-item href="#" disabled>Disabled</b-nav-item>
            </b-navbar-nav>
        </b-collapse>
        </b-navbar>
</template>

<script>
    import Brand from './Brand';
    import Items from './Items';

    export default {
        name: "Nav",
        components: {
            Brand, Items
        },
        data() {
            return {
                isOpen: false
            }
        },
        methods: {
            onToggleMenu() {
                this.isOpen = !this.isOpen
            }

        }
    }
</script>

<style scoped>

</style>