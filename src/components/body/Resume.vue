<template>
    <section class="sobre">
        <div class="container">
            <div class="row align-items-center">
                <div class="cabecalho col-lg-12">
                    <div class="cabecalho_barra col-lg-5" id="sobre"></div>
                    <h3 class="col-lg-2">{{title}}</h3>
                    <div class="cabecalho_barra col-lg-5"></div>
                </div>
            </div>
            <div class="row">
                <div class="sobre_img col-lg-6 offset-lg-0 col-md-8 offset-md-2 col-xl-5 offset-xl-1 animated slideInLeft">
                    <img src="../../assets/imgs/ABOUT-ME.jpg">

                </div>
                <div class="sobre_text col-12 offset-0 col-sm-12 offset-sm-0 col-lg-6 offset-lg-0 col-md-8 offset-md-2 col-xl-5 animated slideInRight">
                    <p v-html="content"></p>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
    export default {
        name: "Resume",
        data(){
            return {
            title: 'Korvax',
            content: 'Espécie de alienígenas do qual evoluiram de uma inteligência digital, seguidores e padres de Atlas, os mais legalzão do universo queria ser um delees pq eles são amigos dos travellers'
            }
        }
    }
</script>

<style scoped>

</style>