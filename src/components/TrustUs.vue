<template>
    <section class="trust-us">
        <div class="container">
            <div class="row">
                <div class="col-sm-12 text-center m-b-20">
                    <h1>They trust us</h1>
                </div>
            </div>
            <div class="row client-row client-big p-b-30">
                <div :class='col' v-for="client_img in client_imgs">
                    <img :src="client_img.url" :alt="client_img.alt">
                </div>
                <!-- <div :class="col">
                    <img src="https://www.mobapi.com/uploads/2017/09/client-edf.png" alt="EDF Guyane">
                </div>
                <div class="col-md-2 col-xs-4">
                    <img src="https://www.mobapi.com/uploads/2017/09/client-po.png" alt="Plastic Omnium">
                </div>
                <div class="col-md-2 col-xs-4">
                    <img src="https://www.mobapi.com/uploads/2017/09/client-mcdo.png" alt="Mc Donald's">
                </div>
                <div class="col-md-2 col-xs-4">
                    <img src="https://www.mobapi.com/uploads/2017/09/client-fitnesspark.png" alt="Fitness Park">
                </div>
                <div class="col-md-2 col-xs-4">
                    <img src="https://www.mobapi.com/uploads/2017/09/client-madiana.png" alt="Cinéma Madiana">
                </div>
                <div class="col-md-2 col-xs-4">
                    <img src="https://www.mobapi.com/uploads/2017/09/client-greentechnologie.png" alt="Green Technologie">
                </div> -->
            </div>
        </div>
    </section>
</template>

<script>
export default {
    data() {
        return {
            col:'col-md-2 col-xs-4',
            client_imgs:[
                {
                    url:'https://www.mobapi.com/uploads/2017/09/client-edf.png',
                    alt:'EDF Guyane'
                },
                {
                    url:'https://www.mobapi.com/uploads/2017/09/client-po.png',
                    alt:'Plastic Omnium'
                },
                {
                    url:'https://www.mobapi.com/uploads/2017/09/client-mcdo.png',
                    alt:'Mc Donalds'
                },
                {
                    url:'https://www.mobapi.com/uploads/2017/09/client-fitnesspark.png',
                    alt:'Fitness Park'
                },
                {
                    url:'https://www.mobapi.com/uploads/2017/09/client-madiana.png',
                    alt:'Cinéma Madiana'
                },
                {
                    url:'https://www.mobapi.com/uploads/2017/09/client-greentechnologie.png',
                    alt:'Green Technologie'
                }
            ]
        }
    }

}

</script>
<style>
.m-b-20 {
    margin-bottom: 20px;
}
.p-b-30 {
    padding-bottom: 30px !important;
}
.client-row {
    overflow: hidden;
    text-align: center;
    line-height: 0;
}
.client-big img {
    max-height: 100%;
    max-width: 100%;
    filter: grayscale(100%);
}
.client-row img {
    opacity: 0.6;
    filter: grayscale(100%);
}
.client-big img:hover{
    max-height: 100%;
    max-width: 100%;
    filter: grayscale(0);
    transition:.3s;
}
.client-row img:hover {
    opacity: 1.0;
}
</style>