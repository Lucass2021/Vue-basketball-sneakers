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
        width: 18.75rem;
        background: #F3F7FF;
        padding:1.875rem;
    }

    .text-container{
        width: 18.75rem;
    }

    .text-container h4{
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        font-size: 1.125rem;
        line-height: 1.25rem;
        margin-top: 1.25rem;
        margin-bottom: 0.313rem;
    }

    .text-container h5{
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        font-size: 1.125rem;
        margin-bottom: 0.625rem;
        color: #7CA2F4;
    }

    .text-container p{
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        font-size: 1.25rem;
    }

    @media only screen and (max-width: 1000px) {
        .text-container{
            text-align: center;
            margin-bottom: 3.125rem;
        }

        .text-container:last-child{
            margin-bottom: 0;
        }

        .img-container img{
            width: 12.5rem;
            padding: 1.25rem;
        }
    }

</style>