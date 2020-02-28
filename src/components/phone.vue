<template>
  <div id="container">
    <div id="container-content">
      <div class="container-content-top">
        <div class="container-content-top-left">手机</div>
        <div class="container-content-top-right">
          <div class="container-content-top-right-left">查看全部</div>
          <div class="container-content-top-right-right">
            <i class="el-icon-arrow-right"></i>
          </div>
        </div>
      </div>
      <div class="container-content-main">
        <div class="container-content-main-left">
          <img
            src="//cdn.cnbj1.fds.api.mi-img.com/mi-mall/574c6643ab91c6618bfb2d0e2c761d0b.jpg?thumb=1&w=293&h=768&f=webp&q=90"
            alt
          />
        </div>
        <div class="container-content-main-right">
      
          <div class="container-content-main-right-item">
            <div>
              <img src="../assets/img/5.webp" width="100%" alt />
            </div>
            <div class="item-name">Redmi K20 Pro 6GB+128GB</div>
            <div class="item-specfic">骁龙855， 弹出全面屏</div>
            <div class="item-price">
              2299元
              <del>2599元</del>
            </div>
          </div>
       
          <div class="container-content-main-right-item">
            <div>
              <img src="../assets/img/5.webp"  alt />
            </div>
            <div class="item-name">Redmi K20 Pro 6GB+128GB</div>
            <div class="item-specfic">骁龙855， 弹出全面屏</div>
            <div class="item-price">
              2299元
              <del>2599元</del>
            </div>
          </div>

          <div class="container-content-main-right-item">
            <div>
              <img src="../assets/img/5.webp"  alt />
            </div>
            <div class="item-name">Redmi K20 Pro 6GB+128GB</div>
            <div class="item-specfic">骁龙855， 弹出全面屏</div>
            <div class="item-price">
              2299元
              <del>2599元</del>
            </div>
          </div>
          <div class="container-content-main-right-item">
            <div>
              <img src="../assets/img/5.webp" alt />
            </div>
            <div class="item-name">Redmi K20 Pro 6GB+128GB</div>
            <div class="item-specfic">骁龙855， 弹出全面屏</div>
            <div class="item-price">
              2299元
              <del>2599元</del>
            </div>
          </div>
          <div class="container-content-main-right-item">
            <div>
              <img src="../assets/img/5.webp" alt />
            </div>
            <div class="item-name">Redmi K20 Pro 6GB+128GB</div>
            <div class="item-specfic">骁龙855， 弹出全面屏</div>
            <div class="item-price">
              2299元
              <del>2599元</del>
            </div>
          </div>
          <div class="container-content-main-right-item">
            <div>
              <img src="../assets/img/5.webp"  alt />
            </div>
            <div class="item-name">Redmi K20 Pro 6GB+128GB</div>
            <div class="item-specfic">骁龙855， 弹出全面屏</div>
            <div class="item-price">
              2299元
              <del>2599元</del>
            </div>
          </div>
          <div class="container-content-main-right-item">
            <div>
              <img src="../assets/img/5.webp" alt />
            </div>
            <div class="item-name">Redmi K20 Pro 6GB+128GB</div>
            <div class="item-specfic">骁龙855， 弹出全面屏</div>
            <div class="item-price">
              2299元
              <del>2599元</del>
            </div>
          </div>
          <div class="container-content-main-right-item">
            <div>
              <img src="../assets/img/5.webp" width="100%" alt />
            </div>
            <div class="item-name">Redmi K20 Pro 6GB+128GB</div>
            <div class="item-specfic">骁龙855， 弹出全面屏</div>
            <div class="item-price">
              2299元
              <del>2599元</del>
            </div>
          </div>
        </div>
      </div>
      <div class="container-content-footer">
        <img src="//cdn.cnbj1.fds.api.mi-img.com/mi-mall/41d16e66381cfeda7b6b39ab67678d5e.jpg?thumb=1&w=1533&h=150&f=webp&q=90"
         width="100%"
         alt="">
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
#container {
  background-color: #f5f5f5;
  width: 100%;
}
#container-content {
  width: 1226px;
  margin: 0 auto;
}
.container-content-top {
  display: flex;
  justify-content: space-between;
}
.container-content-top-left {
  font-size: 22px;
  line-height: 58px;
}
.container-content-top-right {
  display: flex;
  justify-content: center;
  align-items: center;
}
.container-content-top-right-right {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 20px;
  height: 20px;
  border-radius: 50%;
  background-color: #b0b0b0;
  margin-left: 10px;
}
.container-content-main {
  display: flex;
}
.container-content-main-left {
  /* width: 234px;
  height: 614px; */
}
.container-content-main-left img {
  width: 234px;
  height: 614px;
}
.container-content-main-right {
  display: flex;
  flex-wrap: wrap;
}
.container-content-main-right-item {
  width: 232px;
  height: 305px;
  margin-left: 15px;
  background-color: #ffffff;
  text-align: center;
  overflow: hidden;

}
.container-content-main-right-item:hover{
  transform: scale3d(1.05,1.05,1.05);
  transition: all 0.3s;
  overflow: hidden;
  
}
.container-content-main-right-item img{
  width: 90%;
  height: 90%;
}
.item-name {
  white-space: nowrap;
}
.item-specfic {
  color: #d6d6d6;
  font-size: 14px;
  margin-top: 2px;
}
.item-price {
  color: #f8681f;
  margin-top: 20px;
}
.item-price del {
  color: #d6d6d6;
}
.container-content-footer{
  margin-top: 20px;
  padding-bottom:20px;
}
</style>