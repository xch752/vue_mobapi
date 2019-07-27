<template>
    <section class="foot-carousel">
        <div class="container">
            <div class="row">
                <div class="col-sm-10 col-sm-offset-1 col-md-8 col-md-offset-2 text-center">
                    <h1 class="jumbo-h1">DO YOU WANT</h1>
                    <div id="myCarousel" class="carousel slide">
                        <div class="carousel-inner">
                            <div class="item active">
                                <div>to save energy?</div>
                            </div>
                            <div class="item">
                                <div>to optimise your activity?</div>
                            </div>
                            <div class="item">
                                <div>to promote open innovation?</div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {

}
$(function(){
                $('#myCarousel').carousel({interval:2000});
            })
</script>
<style>
section.foot-carousel{
    font-family: OpenSans-Semibold;
    background: #504b57;
    padding-top: 60px;
    padding-bottom: 60px;
}
h1.jumbo-h1{
    margin: 0;
    color: white;
    font-size: 40px;
    line-height: 50px;
    font-weight: 300;
    text-transform: uppercase;

}
.carousel.slide{
    overflow: hidden;
    text-overflow:ellipsis;
    white-space: nowrap;
    color: white;
    font-weight: 700;
    font-size: 40px;
    line-height: 50px;
}

</style>