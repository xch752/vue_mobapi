<template>
  <nav class="navbar navbar-default navbar-fixed-top">
  <div class="container-fluid">
    <div class="navbar-header">
      <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1" aria-expanded="false">
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
      </button>
      <a class="navbar-brand" href="#"><img class ="Brand" alt="Brand" src="https://23kri02j3rke414ynf4dgx2i-wpengine.netdna-ssl.com/img/mobapi-logo.png"></a>
    </div>

    <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
      <ul class="nav navbar-nav">
        <li><a href="#">SOLUTION<span class="sr-only">(current)</span></a></li>
        <li><a href="#">TECHNOLOGY</a></li>
        <li><a href="#">PROJECT</a></li>
        <li><a href="#">BLOG</a></li>
      </ul>
    </div><!-- /.navbar-collapse -->
  </div><!-- /.container-fluid -->
</nav>
</template>

<script>
export default {

}
</script>
<style>
.navbar {
    min-height:60px;
    background-color: rgb(80, 70, 87);
    margin-bottom: 0px;
    -moz-box-shadow:0px 1px 10px #333333; -webkit-box-shadow:0px 1px 10px #333333; box-shadow:0px 1px 10px #333333;
}
.navbar-default {
    border: 0;
}
.navbar-nav {
    margin: 0px -15px;
}
.navbar-header{
    min-height:60px;
}
.navbar-default .navbar-toggle {
    margin-top: 13px;
    border-color: #ddd0;
}
.navbar-default .navbar-toggle .icon-bar {
    background-color: white;
}
.navbar-default .navbar-toggle:focus, .navbar-default .navbar-toggle:hover {
    background-color: #ddd0;
}
.navbar-collapse{
    border: 0;
    border-color: rgb(80, 70, 87);
}
.Brand{
    margin-top: 10px;
    margin-left: 20px;
    margin-right: 20px;
    max-height: 40px;
    position: relative;
    bottom: 16px;
}
/* .navbar-default .navbar-brand {
    color: #ffffff;
}
.navbar-default .navbar-toggle .icon-bar {
    background-color: #ffffff;
} */
.navbar .nav > li > a{
    text-align: center;
    margin-top: 5px;
    margin-left: 40px;
    margin-right: 40px;
    color: white;    
}
.navbar .nav >li >a:visited{
    color: white;
    background-color: #0000ff;
}
.navbar .nav > li > a:hover {
    transition:.5s ease-in;
    color: #1FCC6E;
}


</style>