<template>
    <div class="offset-4 col-8">
        <h1>{{title}}</h1>
        <p>{{subtitle}}</p>
    </div>
</template>

<script>
    export default {
        name: "DescriptionText",
        data () {
            return {
                title: 'NMS',
                subtitle: 'Melhor jogo de exploração espacial da terra'
            }
        }
    }
</script>

<style scoped>

</style>