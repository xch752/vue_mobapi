<template>
    <section class="our-expertise">
        <div class="container align-vertical" style="padding-top: 0px;">
            <div class="row">
                <div class="col-sm-12 text-center m-b-30">
                    <h1>Our expertise</h1>
                </div>
            </div>
            <div class="row">
                <div class="col-md-1">
                    <img :src="expertise_imgs[0].url">
                </div>
                <div class="col-md-5">
                    <h1 class="expertise-title">
                        <span>SMART BUILDING</span>
                         / Manage your buildings' energy consumption
                    </h1>
                    <p class="lead">
                        Air conditioning, power, heating, humidity: connected devices help you reduce your everyday expenses.
                    </p>
                </div>
                <div class="col-md-1">
                    <img :src="expertise_imgs[1].url">
                </div>
                <div class="col-md-5">
                    <h1 class="expertise-title">
                        <span>SMART INDUSTRY</span>
                         / Modernize your manufacturing tools
                    </h1>
                    <p class="lead">
                        The Industry of the Future is open to you today: set up the right tools to improve your productivity
                    </p>
                </div>
            </div>
            <div class="row">
                <div class="col-md-1">
                    <img :src="expertise_imgs[2].url">
                </div>
                <div class="col-md-5">
                    <h1 class="expertise-title">
                        <span>SMART CITY</span>
                         / Make your area smarter
                    </h1>
                    <p class="lead">
                        Digitize your city to optimize the services offered and improve internal processes.
                    </p>
                </div>
                <div class="col-md-1">
                    <img :src="expertise_imgs[3].url">
                </div>
                <div class="col-md-5">
                    <h1 class="expertise-title">
                        <span>OPEN DATA</span>
                         / Start your open data policy
                    </h1>
                    <p class="lead">
                        Get involved with Open Data by making your data public and accessible to all.
                    </p>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    data() {
        return {
            expertise_imgs:[
                {url:'https://www.mobapi.com/uploads/2017/09/smart-building.png'},
                {url:'https://www.mobapi.com/uploads/2017/09/smart-industry.png'},
                {url:'https://www.mobapi.com/uploads/2017/09/smart-city.png'},
                {url:'https://www.mobapi.com/uploads/2017/09/open-data.png'},
            ]
        }
    }

}

</script>
<style>
section:nth-of-type(odd) {
    background: #f4f4f4;
}
section {
    padding-top: 80px;
    padding-bottom: 80px;
    position: relative;
    overflow: hidden;
}
.our-expertise .row {
    margin-bottom: 30px;
}
.m-b-30 {
    margin-bottom: 30px;
}
.accueil section h1, .home section h1 {
    margin-bottom: 12px;
}
.our-expertise img {
    max-width: 80px;
    margin: 0 auto;
    display: block;
    margin-bottom: 20px;
    height: auto;
}
.our-expertise .row .col-md-5 {
    padding-left: 60px;
}
.our-expertise h1.expertise-title {
    margin-top: 0;
    font-size: 24px;
    line-height: 32px;
}
.our-expertise h1 span {
    font-weight: 800;
    color: #14CC71;
}
p.lead {
    font-size: 16px;
    line-height: 30px;
    font-weight: normal;
    padding-bottom: 18px;
}
</style>