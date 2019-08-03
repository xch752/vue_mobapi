<template>
    <section class="steps">
        <div class="container">
            <div class="row">
                <div class="col-sm-12 text-center m-b-20">
                    <h1>
                        <strong>3 steps</strong>
                         to take fully advantage of your data
                    </h1>
                </div>
            </div>
            <div class="row row-centered">
                <div :class="col" v-for="icon of icons"> 
                    <div class="feature feature-icon-steps">
                        <div class="step-icon">
                            <img :src="icon.url" alt="">
                            <h2>
                                <span>{{icon.id}}/</span>
                                {{icon.title}}
                            </h2>
                            <div>{{icon.content}}</div>
                        </div>
                    </div>
                </div>
                <!-- <div class="col-md-3 col-sm-6 clearfix text-center col-centered">
                    <div class="feature feature-icon-steps">
                        <div class="step-icon">
                            <img src="https://23kri02j3rke414ynf4dgx2i-wpengine.netdna-ssl.com/wp-content/uploads/2017/02/MOBAPI-Step-Collect.png" alt="">
                            <h2>
                                <span>1/</span>
                                COLLECTION
                            </h2>
                            <div>of your data</div>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-md-offset-1 col-sm-6 clearfix text-center col-centered">
                    <div class="feature feature-icon-steps">
                        <div class="step-icon">
                            <img src="https://23kri02j3rke414ynf4dgx2i-wpengine.netdna-ssl.com/wp-content/uploads/2017/02/MOBAPI-Step-Transform.png" alt="">
                            <h2>
                                <span>2/</span>
                                PROCESSING
                            </h2>
                            <div>in real time</div>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-md-offset-1 col-sm-6 clearfix text-center col-centered">
                    <div class="feature feature-icon-steps">
                        <div class="step-icon">
                            <img src="https://23kri02j3rke414ynf4dgx2i-wpengine.netdna-ssl.com/wp-content/uploads/2017/09/MOBAPI-Step-visualize.png" alt="">
                            <h2>
                                <span>3/</span>
                                PUBLICATION
                            </h2>
                            <div>in dashboards</div>
                        </div>
                    </div>
                </div> -->
            </div>
            <div class="row text-center  m-t-50">
                <div class="text-center col-sm-10 col-sm-offset-1"></div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    data(){
        return {
            col:'col-md-3 col-sm-6 clearfix text-center col-centered',
            icons:[
                {
                    id:'1',
                    url:'https://23kri02j3rke414ynf4dgx2i-wpengine.netdna-ssl.com/wp-content/uploads/2017/02/MOBAPI-Step-Collect.png',
                    title:'COLLECTION',
                    content:'of your data'
                },
                {
                    id:'2',
                    url:'https://23kri02j3rke414ynf4dgx2i-wpengine.netdna-ssl.com/wp-content/uploads/2017/02/MOBAPI-Step-Transform.png',
                    title:'PROCESSING',
                    content:'in real time'
                },
                {
                    id:'3',
                    url:'https://23kri02j3rke414ynf4dgx2i-wpengine.netdna-ssl.com/wp-content/uploads/2017/09/MOBAPI-Step-visualize.png',
                    title:'PUBLICATION',
                    content:'in dashboards'
                }
            ]
        }
    }
}

</script>
<style>
h2 {
    font-size: 28px;
    line-height: 44px;
}
.row-centered{
    text-align: center;
}
.col-centered {
    display: inline-block;
    float: none;
    margin-right: -4px;
}
.feature {
    overflow: hidden;
}
img {
    max-width: 100%;
    height: auto;
}
.feature-icon-steps h2 {
    font-weight: 700;
}
.feature-icon-steps h2 span {
    font-weight: 100;
    font-size: 40px;
}
.feature-icon-steps > div {
    font-size: 16px;
}

</style>