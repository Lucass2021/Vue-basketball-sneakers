<template>
    <div class="sneaker-container">
        <div class="img-container">
            <img src="../assets/sneakers/jordan/jordan-green.png" alt="">
        </div>
        <div class="text-container">
            <h4>Air Jordan 1 Mid Dutch Green</h4>
            <h5>Tênis Air Jordan</h5>
            <p>R$ 1199,99</p>
        </div>
    </div>
</template>

<script setup>

</script>

<style scoped>

    .sneaker-container{
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
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

</style>