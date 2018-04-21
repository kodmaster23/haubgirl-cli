<template>
    <div class="col-md-10 offset-1">
        <div class="row align-items-center bloco-tudo">
            <div class="col-3 bloco-proximo">
                <h3>Próximo</h3>
                <h1>Show</h1>
            </div>
            <div class="col-2 bloco-tempo">
                <h3>Dias</h3>
                <h2>05</h2>
            </div>
            
            <div class="col-2  bloco-tempo">
                <h3>Horas</h3>
                <h2>23</h2>
            </div>
            <div class="col-2  bloco-tempo">
                <h3>Minutos</h3>
                <h2>10</h2>
            </div>
            <div class="col-2  bloco-tempo">
                <h3>Segundos</h3>
                <h2>36</h2>
            </div>
        </div>
        <div class="row align-items-center">
            <div class="col-8 offset-5">
                <button class="btn btn-primary">ACESSAR</button>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Timer"
    }
</script>

<style scoped>
    .bloco-tudo{
        background-color: rgba(255, 235, 205, 0.5);
        background-opacity: 0.5;
    }
    .bloco-proximo{

    }
    .bloco-tempo{
        background-color: rgba(255,255,255,0.1);
        text-align: center;
        font-family: 'Gadugi';
        font-weight: bold;
        color: black;
    }
</style>