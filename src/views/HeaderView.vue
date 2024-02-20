<template>

<main>
    <header>
        <img :src="caminhodaFoto" alt="">
        <div>
            <h2>QUEM SOMOS</h2>
            <h2><a href="">CONTATO</a></h2>   
        </div>
        <div>
            <button>RIFA SOLIDÁRIA</button>
        </div> 
        <div>
            <img :src="caminhodosEmojis" alt="Redes Sociais">
        </div>
    </header>
</main>
    
</template>

<script>
export default{
    data(){
        return{
            caminhodaFoto: '/logo.png',
            caminhodosEmojis: '/emojis.png'
        }
    }
}

</script>
<style>
    a{
        color: inherit;
        text-decoration: none;
    }
    header{
        display: flex;
        height: 120px;
        background-color: aqua;
        justify-content: space-between  ;
    }
</style>