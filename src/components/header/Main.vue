<template>
    <section class="header-component">
        <div class="d-flex flex-row h-100 justify-content-center" style="background-color: black">
            <div class="row">
              <Nav/>
            </div>

            <div class="align-self-center" style="background-color: pink">
                <DescriptionText></DescriptionText>

            </div>

            <div class="align-self-end" style="background-color: yellow">
                <Timer></Timer>
            </div>

        </div>
    </section>
</template>

<script>
    import Nav from './Nav'
    import DescriptionText from './DescriptionText'
    import Timer from './Timer'

    export default {
        name: "Header",
        components : {
            Nav, DescriptionText, Timer
        }
    }
</script>

<style scoped>

    .header-component{
        background-image: url("../../assets/imgs/HEADER-WALL.jpg");
        background-size: cover;
        height: 100vh;
    }


</style>