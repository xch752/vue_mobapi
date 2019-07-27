<template>
    <div>
        <div class="nav-container">
            <Navbar></Navbar>
        </div>
        <div class="main-container">
            <header class="signup">
                <div class="background-image-holder "></div>
                <div class="container">
                    <div class="row">
                        <div class="col-md-10 col-sm-12 text-center">
                            <h1 class="text-white">
                                Connecting the 
                                <span>
                                    unconnected.
                                </span>
                            </h1>
                            <h3 class="text-white">
                                A simple end-to-end connectivity solution,
                                <br>
                                from collection of data to publication into dashboards or APIs.
                            </h3>
                        </div>
                    </div>
                    <div class="row text-center">
                        <div class="text-center col-sm-10 col-sm-offset-1"></div>
                    </div>
                </div>        
            </header>
            <OurExpertise></OurExpertise>
            <TrustUs></TrustUs>
            <UseCases></UseCases>
            <Steps></Steps>
            <FootCarousel></FootCarousel>
            <Footer></Footer>
        </div>
    </div>
</template>

<script>
import Navbar from '../Navbar'
import OurExpertise from '../OurExpertise'
import TrustUs from '../TrustUs'
import UseCases from '../UseCases'
import Steps from '../Steps'
import FootCarousel from '../FootCarousel'
import Footer from '../Footer'
export default {
    components: {
        'Navbar': Navbar,
        'OurExpertise':OurExpertise,
        "TrustUs":TrustUs,
        "UseCases":UseCases,
        "Steps":Steps,
        "FootCarousel":FootCarousel,
        "Footer":Footer
    }
}

</script>
<style>
header.signup {
    padding: 140px 0px 20px 0;
    position: relative;
    overflow: hidden;
    height: auto;
}
header.signup h1 {
    font-size: 32px;
    line-height: 40px;
}
header.signup h1 {
    font-weight: 600;
    font-size: 40px;
    line-height: 56px;
    margin-bottom: 20px;
}
header.signup h1 span {
    color: #1FCC6E;
}
header.signup h3 {
    font-family: "Open Sans", "Helvetica Neue", Helvetica, Arial, sans-serif;
    font-weight: 300;
    font-size: 25px;
    line-height: 42px;
    margin-bottom: 20px;
}
.text-white {
    color: #fff;
}
header .container {
    position: relative;
    z-index: 3;
    margin-bottom: 80px;
    margin-top: 40px;
}
.background-image-holder {
    background: url(https://23kri02j3rke414ynf4dgx2i-wpengine.netdna-ssl.com/img/bg-smartcity.jpg) no-repeat;
    position: absolute;
    top: 0px;
    left: 0px;
    width: 100%;
    height: 100%;
    background-size: cover !important;
    background-position: 50% 90% !important;
    background-repeat: no-repeat;
}
.row {
    margin-left: -15px;
    margin-right: -15px;
}
.col-sm-12 {
    width: 100%;
}

</style>