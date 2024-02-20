<template>

    <footer>
        <div>
            <img :src="imageLogo" alt="Logo">
        </div>
        <div>
            <div>
                <h2>INTITUCIONAL</h2>
                <h3>SOBRE NÓS</h3>
                <h3>AJUDAR</h3>
                <h3>RIFA</h3>
            </div>
        </div>
    </footer>

</template>

<script>
export default{
    data(){
        return{
            imageLogo: '/logo.png'
        }
    }
}
</script>

<style>

</style>