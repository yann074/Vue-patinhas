<template>
<section class="container3">
    <h1>EFETIVIDADE NA CASTRAÇÃO</h1>

    <div>
        <img :src="imageDog" alt="Dog">
        <div>
            <h1>POR QUE CASTRAR?</h1>
            <h3>A castração previne diversos tipos de câncer, como o câncer de
                 mama e próstata em cães e gatos, e também 
                 doenças do útero e ovários em fêmeas.</h3>
        </div>
    </div>
    <div>
        <img :src="imageCat" alt="Cat">
        <div>
            <h1>POR QUE ADOTAR?</h1>
            <h3>A adoção de um animal de estimação é um ato de amor e 
                responsabilidade que traz benefícios tanto para o animal 
                quanto para o tutor. Um animal de estimação pode 
                ser um companheiro leal.</h3>
        </div>
    </div>
</section>
</template>

<script>

    export default{
        data(){
            return{
                imageDog: '/image2.png',
                imageCat: '/image3.png'
            }
        }
    }

</script>

<style>

    .container3{
        display: flex;
        flex-direction: row;
        height: 500px;
    }
</style>