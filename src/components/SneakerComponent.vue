<template>
    <div class="sneaker-container">
        <div class="img-container">
            <img :src="props.img" alt="">
        </div>
        <div class="text-container">
            <h4>{{ props.name }}</h4>
            <h5>{{ props.brand }}</h5>
            <p>{{ props.price }}</p>
        </div>
    </div>
</template>

<script setup>
    import { defineProps } from 'vue';

    const props = defineProps({
        img: String,
        name: String,
        brand: String, 
        price: String,
    })

</script>

<style scoped>

    .sneaker-container{
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
    }

    .sneaker-container:hover{
        cursor: pointer;
    }
    .img-container img{
        width: 300px;
        background: #F3F7FF;
        padding:30px;
    }

    .text-container{
        width: 300px;
    }

    .text-container h4{
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        font-size: 18px;
        line-height: 20px;
        margin-top: 20px;
        margin-bottom: 5px;
    }

    .text-container h5{
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        font-size: 18px;
        margin-bottom: 10px;
        color: #7CA2F4;
    }

    .text-container p{
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        font-size: 20px;
    }

    @media only screen and (max-width: 1000px) {
        .text-container{
            text-align: center;
            margin-bottom: 50px;
        }

        .text-container:last-child{
            margin-bottom: 0px;
        }

        .img-container img{
            width: 200px;
            padding: 20px;
        }
    }

</style>