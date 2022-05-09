<template>
 <div class="rickpages-container">
     <img class="rickpages-img" :src="imagen" alt="">
     <p class="rickpages-name">{{nombre}}</p>
 </div>
</template>

<script>
export default {
    props:['nombre', 'imagen']
}
</script>

<style>
    .rickpages-container{
        display: flex;
        align-items: center;
        margin: 1rem;
        gap: 1rem;
    }
    .rickpages-img{
        border-radius: 50%;
        max-width: 100px;
    }
    .rickpages-name{
        font-size: 2rem;
        color: green;
    }
</style>