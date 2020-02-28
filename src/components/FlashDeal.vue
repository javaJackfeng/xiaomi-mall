<template>
  <div id="flsahdeal-container">
    <div id="flsahdeal-container-content">
      <div class="flsahdeal-container-top">
        <div class="flashdeal-container-top-left">小米闪购</div>
        <div class="flashdeal-container-top-right">
          <div>
            <i class="el-icon-arrow-left"></i>
          </div>
          <div>
            <i class="el-icon-arrow-right"></i>
          </div>
        </div>
      </div>
      <div class="flsahdeal-container-main">
        <div class="flsahdeal-container-main-left">
          <div class="flsahdeal-container-main-left-time">14:00场</div>
          <div class="flsahdeal-container-main-left-icon" style="margin-bottom:40px">
            <img src="../assets/img/thum.svg" alt />
          </div>
          <div class="flsahdeal-container-main-left-lefttimetext" style="margin-bottom:40px">距离结束还有</div>
          <div class="flsahdeal-container-main-left-lefttime">
            <img src="../assets/img/Snipaste_2020-02-27_19-24-51.png" alt />
          </div>
        </div>
        <div class="flsahdeal-container-main-right">
          <div class="flsahdeal-container-main-right-item">
            <img src="../assets/img/flashDeal/baisebijiben.jpg" width="100%" alt />
            <div class="item-name">{{itemName|formatItemName}}</div>
            <div class="item-specfic">纤薄机身，A面金属材质</div>
            <div class="item-price">7499元 <del>8999元</del></div>
          </div>
          <div class="flsahdeal-container-main-right-item">
            <img src="../assets/img/flashDeal/bijiben.png" width="100%" alt />
            <div class="item-name">{{itemName|formatItemName}}</div>
            <div class="item-specfic">纤薄机身，A面金属材质</div>
            <div class="item-price">7499元 <del>8999元</del></div>
          </div>
          <div class="flsahdeal-container-main-right-item">
            <img src="../assets/img/flashDeal/cadiji.jpg" width="100%" alt />
             <div class="item-name">{{itemName|formatItemName}}</div>
            <div class="item-specfic">纤薄机身，A面金属材质</div>
            <div class="item-price">7499元 <del>8999元</del></div>
          </div>
          <div class="flsahdeal-container-main-right-item">
            <img src="../assets/img/flashDeal/chabei.jpg" width="100%" alt />
            <div class="item-name">{{itemName|formatItemName}}</div>
            <div class="item-specfic">纤薄机身，A面金属材质</div>
            <div class="item-price">7499元 <del>8999元</del></div>
          </div>
          <div class="flsahdeal-container-main-right-item">
            <img src="../assets/img/flashDeal/heisebijiben.jpg" width="100%" alt />
            <div class="item-name">{{itemName|formatItemName}}</div>
            <div class="item-specfic">纤薄机身，A面金属材质</div>
            <div class="item-price">7499元 <del>8999元</del></div>
          </div>
          <div class="flsahdeal-container-main-right-item">
            <img src="../assets/img/flashDeal/jianpan.png" width="100%" alt />
            <div class="item-name">{{itemName|formatItemName}}</div>
            <div class="item-specfic">纤薄机身，A面金属材质</div>
            <div class="item-price">7499元 <del>8999元</del></div>
          </div>
          <div class="flsahdeal-container-main-right-item">
            <img src="../assets/img/flashDeal/luyouqihuise.jpg" width="100%" alt />
            <div class="item-name">{{itemName|formatItemName}}</div>
            <div class="item-specfic">纤薄机身，A面金属材质</div>
            <div class="item-price">7499元 <del>8999元</del></div>
          </div>
          <div class="flsahdeal-container-main-right-item">
            <img src="../assets/img/flashDeal/mouse.jpg" width="100%" alt />
            <div class="item-name">{{itemName|formatItemName}}</div>
            <div class="item-specfic">纤薄机身，A面金属材质</div>
            <div class="item-price">7499元 <del>8999元</del></div>
          </div>
        </div>
      </div>
      <div class="flsahdeal-container-footer">
        <img src="//cdn.cnbj1.fds.api.mi-img.com/mi-mall/406c0feca62732acbb2893344486895d.jpg?thumb=1&w=1533&h=150&f=webp&q=90" 
          width="100%"
        alt="">
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      itemName:'小米游戏本电脑15.6" i3 4G 256G 集显 白色'
    }
  },
  filters:{
    formatItemName: function(str){
      let params=str.split('');
      return params.length> 17 ? str.split('').splice(0,17).join('')+'...':str;
    }
  }
};
</script>
<style scoped>
#flsahdeal-container {
  background-color: #f5f5f5;
  width: 100%;
  margin-top: 40px;
}
#flsahdeal-container-content {
  width: 1226px;
  margin: 0 auto;
}
.flsahdeal-container-top {
  display: flex;
  justify-content: space-between;
}
.flashdeal-container-top-left {
  font-size: 22px;
  line-height: 58px;
}
.flashdeal-container-top-right {
  display: flex;
  width: 90px;
}
.flashdeal-container-top-right div {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 45px;
  height: 30px;
  margin-top: 20px;
  border: 1px solid #e0e0e0;
}
.flsahdeal-container-main {
  display: flex;
  justify-content: space-between;
  height: 400px;
  width: 100%;
}
.flsahdeal-container-main-left {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background-color: #f1eded;
  width: 234px;
}
.flsahdeal-container-main-left-time {
  color: #ec363c;
  font-size: 21px;
  margin-bottom: 40px;
}
.flsahdeal-container-main-right {
  display: flex;
  flex-wrap: wrap;
  width: 978px;
  height: 100%;
  overflow: hidden;
}
.flsahdeal-container-main-right .flsahdeal-container-main-right-item{
  width: 234px;
  margin-left: 10px;
  border-top: 0.5px solid red;
  background-color: #fafafa;
  height: 100%;
  text-align: center;
}
.item-name{
  white-space: nowrap;
}
.item-specfic{
  color:#d6d6d6;
  font-size: 14px;
  margin-top: 2px;
}
.item-price{
  color:#f8681f;
  margin-top:20px;
}
.item-price del{
  color:#d6d6d6;
}
.flsahdeal-container-footer{
  margin-top: 20px;
  padding-bottom:20px;
}
</style>