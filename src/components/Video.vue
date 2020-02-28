<template>
  <div id="video-container">
    <div id="video-container-content">
      <div class="container-content-top">
        <div class="container-content-top-left">视频</div>
        <div class="container-content-top-right">
          <div class="container-content-top-right-left">查看全部</div>
          <div class="container-content-top-right-right">
            <i class="el-icon-arrow-right"></i>
          </div>
        </div>
      </div>
      <div class="container-content-main">
        <div class="container-content-main-item">
          <img
            src="//cdn.cnbj1.fds.api.mi-img.com/mi-mall/2fd26bb99b723337a2f8eaba84f7d5bb.jpg?thumb=1&w=370&h=225&f=webp&q=90"
            width="296"
            height="180"
            alt
          />
          <div class="main-item-palyer">
            <i class="el-icon-video-play video-play-icon"></i>
          </div>
          <!-- <video controls width="296" height="180">
             <source src="https://cdn.cnbj1.fds.api.mi-img.com/mi-mall/e25d81c4922fca5ebe51877717ef9b76.mp4">
          </video>-->
          <div class="main-item-alt">小米10 8k手机拍大片</div>
        </div>
        <div class="container-content-main-item">
          <img
            src="//cdn.cnbj1.fds.api.mi-img.com/mi-mall/a8dd25cab48c60fc6387b9001eddc3f9.jpg?thumb=1&w=370&h=225&f=webp&q=90"
            width="296"
            height="180"
            alt
          />
          <div class="main-item-palyer">
            <i class="el-icon-video-play video-play-icon"></i>
          </div>
          <!-- <video controls width="296" height="180">
             <source src="https://cdn.cnbj1.fds.api.mi-img.com/mi-mall/eadb8ddc86f1791154442a928b042e2f.mp4">
          </video>-->
          <div class="main-item-alt">小米10 8k手机拍大片</div>
        </div>
        <div class="container-content-main-item">
          <img
            src="//cdn.cnbj1.fds.api.mi-img.com/mi-mall/b4004fc968de331f702585d58b15aba2.jpg?thumb=1&w=370&h=225&f=webp&q=90"
            width="296"
            height="180"
            class="main-item-img"
            alt
          />
          <div class="main-item-palyer">
            <i class="el-icon-video-play video-play-icon"></i>
          </div>
          <!-- <video controls width="296" height="180">
             <source src="https://cdn.cnbj1.fds.api.mi-img.com/mi-mall/eadb8ddc86f1791154442a928b042e2f.mp4">
          </video>-->
          <div class="main-item-alt">小米10 8k手机拍大片</div>
        </div>
        <div class="container-content-main-item">
          <img
            src="//cdn.cnbj1.fds.api.mi-img.com/mi-mall/395fdedf0f40206032397e33beed756e.jpg?thumb=1&w=370&h=225&f=webp&q=90"
            width="296"
            height="180"
            alt
          />
          <div class="main-item-palyer">
            <i class="el-icon-video-play video-play-icon"></i>
          </div>
          <!-- <video controls width="296" height="180">
             <source src="https://cdn.cnbj1.fds.api.mi-img.com/mi-mall/1443581f88b733750c7763b2b3d67c52.mp4">
          </video>-->
          <div class="main-item-alt">小米10 8k手机拍大片</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
#video-container {
  background-color: #f5f5f5;
  width: 100%;
}
#video-container-content {
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
  justify-content: space-between;
  padding-bottom: 20px;
}
.container-content-main-item {
  position: relative;
  background-color: #fff;
}
.main-item-alt {
  margin-top: 30px;
  margin-bottom: 50px;
  text-align: center;
}
.main-item-palyer {
  position: absolute;
  left: 20px;
  bottom: 45%;
  z-index: 10;
}
.video-play-icon {
  font-size: 30px;
  width: 30px;
  /* color: #fff; */
  color: #fd6310;
}
.main-item-img:hover {
}

</style>