<template>
    <section class="contato" >
        <div class="container">
            <div class="row">
                <div class="cabecalho col-lg-12" id="contato">
                    <div class="cabecalho_barra col-lg-5"></div>
                    <h3 class="col-lg-2">Contato</h3>
                    <div class="cabecalho_barra col-lg-5"></div>
                </div>
            </div>

            <div class="row">
                <div class="formulario col-lg-8 offset-lg-1">
                    <form class="form_contato">
                        <div class="form-row">
                            <div class="form-group col-lg-5">
                                <label for="inputEmail4">Nome</label>
                                <input type="email" class="form-control" id="inputEmail4" placeholder="">
                            </div>
                            <div class="form-group col-lg-6 offset-lg-1">
                                <label for="inputPassword4">E-mail</label>
                                <input type="password" class="form-control" id="inputPassword4" placeholder="">
                            </div>
                        </div>
                        <div class="form-group">
                            <label for="exampleFormControlTextarea1">Mensagem</label>
                            <textarea class="form-control" id="exampleFormControlTextarea1" rows="5"></textarea>
                        </div>
                        <button class="btn_contato col-lg-2">Enviar</button>
                    </form>

                </div>
            </div>

        </div>
    </section>
</template>

<script>
    export default {
        name: "Contact"
    }
</script>

<!--<style scoped>-->

    <!--.contato{-->
        <!--background-image:url("../assets/imgs/bg_contato.png");-->
        <!--width: 100%;-->
        <!--height: auto;-->
        <!--padding-bottom: 50px;-->
        <!--background-size: cover;-->
        <!--background-position: left top;-->
    <!--}-->

    <!--.form{-->
        <!--color: white;-->
    <!--}-->

    <!--.form_contato label{-->
        <!--color: #bbbbbb;-->
        <!--margin-bottom: 0px;-->
        <!--font-size: 20px;-->
        <!--font-family: 'Gadugi';-->
    <!--}-->

    <!--.form_contato input, .form_contato textarea{-->
        <!--border-radius: 0px;-->
        <!--border: 0px;-->
        <!--background-color: white;-->
        <!--opacity: 0.2;-->
        <!--color: white;-->
    <!--}-->

    <!--.btn_contato{-->
        <!--margin: 0;-->
        <!--height: 40px;-->
        <!--border: 0px;-->
        <!--color: white;-->
        <!--background-color: #fc138c;-->
        <!--font-size: 20px;-->
        <!--font-family: 'Gadugi';-->
        <!--font-weight: bolder;-->
        <!--float: right;-->
    <!--}-->

<!--</style>-->