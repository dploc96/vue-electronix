<template>
  <div id="header">
    <div class="header__logo"> <a href="#"><img src="images/logo.png" alt="" border="0" width="237" height="140" /></a> </div>
    <div class="header__right">
      <div class="header__top-divider">
        <img src="images/header_divider.png" alt="" width="1" height="164" />
      </div>
      <div class="header__right-oferta">
        <div class="right-oferta__content"> 
          <img src="images/laptop.png" width="94" height="92" alt="" border="0" class="right-oferta__img" />
          <div class="right-oferta__details">
            <div class="right-oferta__details-title">Samsung GX 2004 LM</div>
            <div class="right-oferta__details-text"> Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco </div>
            <a href="details.html" class="right-oferta__details-link">details</a> 
          </div>
        </div>
        <div class="right-oferta__pagination"> 
          <span class="right-oferta__pagination-current">1</span> <a href="#">2</a> <a href="#">3</a> <a href="#">4</a> <a href="#">5</a> 
        </div>
      </div>
      <div class="header__top_divider">
        <img src="images/header_divider.png" alt="" width="1" height="164" />
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
#header {
  width: 1000px;
  height: 173px;
  margin: auto;
  background: url(/images/header_bg.jpg) no-repeat center;
  background-position: 0px 0px;
}

.header__logo {
  float:left;
  padding: 15px;
} 

.header__right{
  width: 600px;
  height: 164px;
  float: left;
  padding: 0 0 0 50px;
}

.header__top-divider {
  float: left;
  width: 1px;
  height: 164px;
}

.header__right-oferta {
  float: left;
  width: 538px;
  padding: 15px 30px 0 30px;
}

.right-oferta__img {
  float: left;
  padding: 0 0 10px 0;
}

.right-oferta__details{
  width: 400px;
  float: left;
  padding: 0 0 0 30px;
}

.right-oferta__details-title {
  font-size: 15px;
  color: #b72c24;
  font-weight: bold;
}

.right-oferta__details-text {
  padding: 5px 0 5px 0;
  font-size: 12px;
  color: #FFFFFF;
  text-align: justify;
  line-height: 15px;
}

.right-oferta__details-link {
  float:right;
  display:block;
  width:83px;
  height:21px;
  margin:5px 0 0 0;
  padding-left:5px;
  background:url(/images/details_bt_bg.gif) no-repeat center;
  text-align:center;
  line-height:21px;
  text-decoration:none;
  color:#000000;
}

.right-oferta__pagination {
  clear:both;
  padding:10px 0 0 0;
  margin:5px;
  text-align:center;
  float:left;
  font-size:10px;
}

.right-oferta__pagination a {
  width:22px;
  height:22px;
  display:block;
  float:left;
  margin:0 0 0 5px;
  line-height:23px;
  text-align:center;
  background:url(/images/pag_bg.gif) no-repeat center;
  text-decoration:none; 
  color:#9d8b8b;
}

.right-oferta__pagination a:hover {
  width:22px;
  height:22px;
  display:block;
  float:left;
  line-height:23px;
  text-align:center;
  background:url(/images/pag_bg_a.gif) no-repeat center;
  text-decoration:none; 
  color:#ad1614;
}

.right-oferta__pagination-current {
  width:22px;
  height:22px;
  display:block;
  float:left;
  line-height:23px;
  text-align:center;
  background:url(/images/pag_bg_a.gif) no-repeat center;
  text-decoration:none; 
  color:#ad1614;
}
</style>