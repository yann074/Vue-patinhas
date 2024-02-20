<template>
<section>
    <div>
        <img :src="imageDogs" alt="Dogs">
        <h2>XXX</h2>
        <h2>ANIMAIS CASTRADOS</h2>
    </div>
    <div>
        <img :src="imageHouse" alt="House">
    </div>
</section>
</template>

<script>
export default{
    data(){
        return{
            imageHouse: '/houseimg.png',
            imageDogs: '/cachorrosjnt.png'
        }
    }
}
</script>

<style>

</style>
