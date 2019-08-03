<template>
    <section class="use-cases">
        <div class="container">
            <div class="row">
                <div class="col-sm-12 text-center m-b-30">
                    <h1>Use cases</h1>
                </div>
            </div>
            <div class="row">
                <div class="col-md-10 col-md-offset-1 col-sm-10 col-sm-offset-1">
                    <ul class="use-cases-ul">
                        <li v-for="usecase_img in usecase_imgs">
                            <div class="title">
                                <img :src="usecase_img.url1" style="width:32px"></img>
                                <img :src="usecase_img.url2" style="width:16px"></img>
                                <img :src="usecase_img.url3" style="width:32px"></img>
                                <span><strong>{{usecase_img.strong}}</strong>{{usecase_img.span}}</span>
                                <span class="use-case-link"></span>
                            </div>
                        </li>
                        <!-- <li>
                            <div class="title">
                                <i class="streamline-thermometer"><img src="../assets/img/streamline/streamline-thermometer.png" alt="" style="width:32px"></i>
                                <i class="streamline-add-1"><img src="../assets/img/streamline/streamline-add-1.png" alt="" style="width:16px"></i>
                                <i class="streamline-lightbulb-2"><img src="../assets/img/streamline/streamline-lightbulb-2.png" alt=""></i>
                                <span><strong>Identify</strong> energy-hogging appliances</span>
                                <span class="use-case-link"></span>
                            </div>
                        </li>
                        <li>
                            <div class="title">
                                <i class="streamline-factory"><img src="../assets/img/streamline/streamline-factory.png" alt="" style="width:32px"></i>
                                <i class="streamline-add-1"><img src="../assets/img/streamline/streamline-add-1.png" alt="" style="width:16px"></i>
                                <i class="streamline-dashboard-speed-streamline"><img src="../assets/img/streamline/streamline-dashboard-speed-streamline.png" alt=""></i>
                                <span><strong>Gather</strong> manufacturing data easily, thanks to smart devices</span>
                                <span class="use-case-link"></span>
                            </div>
                        </li>
                        <li>
                            <div class="title">
                                <i class="streamline-truck-dump"><img src="../assets/img/streamline/streamline-truck-dump.png" alt="" style="width:32px"></i>
                                <i class="streamline-add-1"><img src="../assets/img/streamline/streamline-add-1.png" alt="" style="width:16px"></i>
                                <i class="streamline-smartphone"><img src="../assets/img/streamline/streamline-smartphone.png" alt=""></i>
                                <span><strong>Optimize</strong> trash collection routes with sensors on the SIGFOX network</span>
                                <span class="use-case-link"></span>
                            </div>
                        </li>
                        <li style="border:0px">
                            <div class="title">
                                <i class="streamline-building-12"><img src="../assets/img/streamline/streamline-building-12.png" alt="" style="width:32px"></i>
                                <i class="streamline-add-1"><img src="../assets/img/streamline/streamline-add-1.png" alt="" style="width:16px"></i>
                                <i class="streamline-chart-board"><img src="../assets/img/streamline/streamline-chart-board.png" alt=""></i>
                                <span><strong>Publish</strong> an open data portal for your municipality</span>
                                <span class="use-case-link"></span>
                            </div>
                        </li> -->
                    </ul>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    data() {
        return {
            usecase_imgs:[
                {
                    url1:require('../assets/img/streamline/streamline-thermometer.png'),
                    url2:require('../assets/img/streamline/streamline-add-1.png'),
                    url3:require('../assets/img/streamline/streamline-lightbulb-2.png'),
                    strong:'Identify',
                    span:'energy-hogging appliances'
                },
                {
                    url1:require('../assets/img/streamline/streamline-factory.png'),
                    url2:require('../assets/img/streamline/streamline-add-1.png'),
                    url3:require('../assets/img/streamline/streamline-dashboard-speed-streamline.png'),
                    strong:'Gather',
                    span:' manufacturing data easily, thanks to smart devices'
                },
                {
                    url1:require('../assets/img/streamline/streamline-truck-dump.png'),
                    url2:require('../assets/img/streamline/streamline-add-1.png'),
                    url3:require('../assets/img/streamline/streamline-smartphone.png'),
                    strong:'Optimize',
                    span:' trash collection routes with sensors on the SIGFOX network'
                },
                {
                    url1:require('../assets/img/streamline/streamline-building-12.png'),
                    url2:require('../assets/img/streamline/streamline-add-1.png'),
                    url3:require('../assets/img/streamline/streamline-chart-board.png'),
                    strong:'Publish',
                    span:' an open data portal for your municipality'
                },

            ]
        }
    }

}

</script>
<style>
.expanding-ul, .use-cases-ul {
    padding:0px;
    position: relative;
    overflow: hidden;
}
.use-cases-ul li {
    line-height: 36px;
}
.use-cases-ul li {
    list-style: none;
    /* text-align: center; */
    border-bottom: 1px solid rgba(0, 0, 0, 0.2);
    padding-bottom: 24px;
    margin-bottom: 24px;
    /* cursor: pointer; */
    font-size: 16px;
}
.use-cases-ul li .title {
    -webkit-transition: all .3s ease;
    -moz-transition: all .3s ease;
    transition: all .3s ease;
}
.use-cases-ul .title i {
    color: #14CC71;
    font-size: 32px;
    display: inline-block;
    margin-right: 24px;
}
.use-cases-ul .title span {
    position: relative;
}
.use-cases-ul .title strong {
    font-weight: 600;
    color: #504b57;
}
.use-case-link {
    padding: 0;
    margin-left: 8px;
}

</style>