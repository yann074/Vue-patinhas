<template>
    <section class="container-frames">
        <div>
            <img :src="imageFrame1" alt="">
            <h3>Castrar seu animal é um ato de amor que demonstra cuidado e responsabilidade. 
                Você protege seu amigo de doenças, previne ninhadas indesejadas e contribui 
                para o controle da população animal.</h3>
        </div>
        <div>
            <img :src="imageFrame2" alt="">
            <h3>A triste realidade dos animais indesejados é um problema que exige atenção e medidas eficazes.
                 São milhares de animais abandonados nas ruas todos os dias, 
                sofrendo de fome, doenças, maus-tratos e a constante ameaça de morte.</h3>
        </div>
        <div>
            <img :src="imageFrame3" alt="">
            <h3>O animal abandonado fica perdido,
                desorientado e com medo.Ele pode sofrer de fome,
                doenças,frio e ser vítima de maus-tratos.
                o amor que não abandona é o que transforma a vida dos animais.</h3>
        </div>
    </section>
</template>

<script>
export default{
    data(){
        return{
            imageFrame1: '/frame1.png',
            imageFrame2: '/frame2.png',
            imageFrame3: '/frame3.png',
            backgroundFundo: '/fundoFrame3.png'

        }
    }
}
</script>

<style>
    .container-frames{
        display: flex;
        height: 400px;
        width: auto;
        background-image: url(./public/fundoFrame3.png);
    }
</style>