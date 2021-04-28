<template>
  <div class="top-bar">
    <div class="top-bar__search">
      <div class="top-bar__search-text"><a href="#">Advanced Search</a></div>
      <input type="text" class="top-bar__search-input" name="search" />
      <input type="image" src="images/search.gif" class="top-bar__search-bt"/>
    </div>
    <div class="top-bar__lang">
      <div class="top-bar__lang-text">Languages:</div>
      <a href="#" class="top-bar__lang-ic"><img src="images/en.gif" alt="" border="0" /></a> <a href="#" class="top-bar__lang-ic"><img src="images/de.gif" alt="" border="0" /></a> 
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style scoped>
.top-bar{
  width:1000px;
  height:38px;
  background-color:#4a4a4a;
}

.top-bar__search{
  float:right;
  width:370px;
  height:32px;
  margin:0px 20px 0 0;
  background:url(/images/top_search_bg.gif) no-repeat center;
}

.top-bar__search-input{
  float:left;
  width:182px;
  height:18px;
  margin:5px 0 0 0 ;
  border:1px solid #dbdbdb;
  border-bottom-color:#ffffff;
  border-right-color:#ffffff;
}

.top-bar__search-text{
  float:left;
  width:110px;
  padding:8px 0 0 15px;
  color:#999999;
}

.top-bar__search-text a{
  color:#999999;
  text-decoration:none;
}

.top-bar__search-bt{
  float:left;
  padding:2px 0 0 15px;
}

.top-bar__lang{
  float:right;
  width:150px;
  padding:8px 0 0 0;
}

.top-bar__lang-text{
  float:left;
  padding:0 5px 0 0;
  color:#b3adad;
}

.top-bar__lang-ic{
  float:left;
  display:block;
  padding:0 5px 0 5px;
}
</style>
