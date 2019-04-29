<template>
  <div class="search-box">
    <div class="search ">
      <input class="search-input" type="text"/>
      <a class="search-btn">搜索</a>
   </div>
    <div class="search-text">
      <a>香奈儿</a>
      <span>|</span>
      <a>奶粉</a>
      <span>|</span>
      <a>家具</a>
    </div>
  </div>
</template>
<script>
    export default {

    }
</script>
<style scoped>
  .search-box{
  width: 428px;
    display: inline-block;
   line-height: normal;
    vertical-align: middle;
  }
  .search{

    width:100%;
    height:40px;
    border:2px solid #ff2d52;
    position: relative;
  }
  .search-input{
    width:100%;
    height: 100%;
    line-height: 38px;
    padding-left: 30px;
    border: 0;
    color: #aaa;
    background:url("../../static/images/search.png") no-repeat 8px center;

  }
.search-text{
  line-height: 23px;
  color: #333;
}
@media (max-width: 748px) {
  .search-box{
    width: 100%;
    text-align: left;
  }
  .search{
    -webkit-border-radius: 25px;
    -moz-border-radius:25px;
    border-radius: 25px;
    overflow: hidden;
  }
}

  .search-input{
    width: 100%;
    height: 100%;
   line-height: 38px;
    border: 0;
  }
  .search-input:focus{
    outline: none;
  }
  .search-btn{
    width: 78px;
    height: 40px;
    display: inline-block;
    background: #ff2d52;
    text-align: center;
    line-height: 38px;
    font-size: 16px;
    color: #fff;
    position: absolute;
    top: 0;
    right: 0;
  }
</style>
