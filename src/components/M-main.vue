<template>
  <div id="M-main-container">
    <div class="site-header">
      <div class="site-header-logo">
        <!-- <img src="../assets/img/img.png" alt="logo"> -->
      </div>
      <div class="site-header-content">
        <ul class="site-header-content-ul">
          <li class="site-header-content-ul-li">小米手机</li>
          <li>Redmi红米</li>
          <li>电视</li>
          <li>笔记本</li>
          <li>家电</li>
          <li>路由器</li>
          <li>智能硬件</li>
          <li>服务</li>
          <li>社区</li>
        </ul>
      </div>
      <div class="site-header-search">
        <el-input placeholder="请输入内容" class="input-with-select" height="55px">
          <el-button slot="append" icon="el-icon-search"></el-button>
        </el-input>
      </div>
    </div>
    <div class="site-content">
      <div class="site-content-left">
        <ul class="site-content-left-ul">
          <li class="site-content-left-ul-li">
            <div>手机 电话卡</div>
            <div class="site-content-left-ul-li-icon">
              <i class="el-icon-arrow-right"></i>
            </div>
          </li>
          <li class="site-content-left-ul-li">
            <div>电视 盒子</div>
            <div class="site-content-left-ul-li-icon">
              <i class="el-icon-arrow-right"></i>
            </div>
          </li>
          <li class="site-content-left-ul-li">
            <div>笔记本 显示器 平板</div>
            <div class="site-content-left-ul-li-icon">
              <i class="el-icon-arrow-right"></i>
            </div>
          </li>
          <li class="site-content-left-ul-li">
            <div>家电 插线板</div>
            <div class="site-content-left-ul-li-icon">
              <i class="el-icon-arrow-right"></i>
            </div>
          </li>
          <li class="site-content-left-ul-li">
            <div>出行 穿戴</div>
            <div class="site-content-left-ul-li-icon">
              <i class="el-icon-arrow-right"></i>
            </div>
          </li>
          <li class="site-content-left-ul-li">
            <div>智能 路由器</div>
            <div class="site-content-left-ul-li-icon">
              <i class="el-icon-arrow-right"></i>
            </div>
          </li>
          <li class="site-content-left-ul-li">
            <div>电源 配件</div>
            <div class="site-content-left-ul-li-icon">
              <i class="el-icon-arrow-right"></i>
            </div>
          </li>
          <li class="site-content-left-ul-li">
            <div>健康 儿童</div>
            <div class="site-content-left-ul-li-icon">
              <i class="el-icon-arrow-right"></i>
            </div>
          </li>
          <li class="site-content-left-ul-li">
            <div>耳机 音箱</div>
            <div class="site-content-left-ul-li-icon">
              <i class="el-icon-arrow-right"></i>
            </div>
          </li>
          <li class="site-content-left-ul-li">
            <div>生活 箱包</div>
            <div class="site-content-left-ul-li-icon">
              <i class="el-icon-arrow-right"></i>
            </div>
          </li>
        </ul>
      </div>
      <div class="site-content-right">
        <div v-for="(item, index) in imgs" :key="index">
            <img v-if="index==num" :src="item" alt="" >
        </div>
        <div class="site-content-right-button-left"><el-button @click="lastPage" icon='el-icon-arrow-left' /></div>
        <div class="site-content-right-button-right"><el-button @click="nextPage" icon='el-icon-arrow-right'/></div>
        <div class="site-content-right-index">
          <div :class="{'current-index':num==0}"></div>
          <div :class="{'current-index':num==1}"></div>
          <div :class="{'current-index':num==2}"></div>
          <div :class="{'current-index':num==3}"></div>
          <div :class="{'current-index':num==4}"></div>
        </div>
      </div>
    </div>
    <div class="site-footer">
       <div class="site-footer-left">
         <div class="site-footer-left-item" >
          <div><img src="https://cdn.cnbj1.fds.api.mi-img.com/mi-mall/82abdba456e8caaea5848a0cddce03db.png?w=48&h=48" alt=""> </div>
          <div><span>小米秒杀</span></div>
         </div>
         <div class="site-footer-left-item">
           <div><img src="https://cdn.cnbj1.fds.api.mi-img.com/mi-mall/806f2dfb2d27978e33fe3815d3851fa3.png?w=48&h=48" alt=""> </div>
          <div><span>企业团购</span></div>
         </div>
         <div class="site-footer-left-item">
           <div><img src="https://cdn.cnbj1.fds.api.mi-img.com/mi-mall/eded6fa3b897a058163e2485532c4f10.png?w=48&h=48" alt=""></div>
          <div><span>F码通道</span></div>
         </div>
         <div class="site-footer-left-item">
           <div><img src="https://cdn.cnbj1.fds.api.mi-img.com/mi-mall/43a3195efa6a3cc7662efed8e7abe8bf.png?w=48&h=48" alt=""></div>
          <div><span>米粉卡</span></div>
         </div>
         <div class="site-footer-left-item">
           <div><img src="https://cdn.cnbj1.fds.api.mi-img.com/mi-mall/f4846bca6010a0deb9f85464409862af.png?w=48&h=48" alt=""></div>
          <div><span>以旧换新</span></div>
         </div>
         <div class="site-footer-left-item">
           <div><img src="https://cdn.cnbj1.fds.api.mi-img.com/mi-mall/9a76d7636b08e0988efb4fc384ae497b.png?w=48&h=48" alt=""></div>
          <div><span>话费充值</span></div>
         </div>
       </div>
       <div class="site-footer-right1">
         <img src="https://cdn.cnbj1.fds.api.mi-img.com/mi-mall/7bc54a61b927dd8c54ddd39a0acf0254.jpg?w=632&h=340" alt="">
       </div>
       <div class="site-footer-right1">
         <img src="https://cdn.cnbj1.fds.api.mi-img.com/mi-mall/94c74e01afe50a86c3a87ff030b85781.jpg?w=632&h=340" alt="">
       </div>
       <div class="site-footer-right1">
         <img src="https://cdn.cnbj1.fds.api.mi-img.com/mi-mall/816a66edef10673b4768128b41804cae.jpg?w=632&h=340" alt="">
       </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      isCurrent:true,
      num:0,
      imgs:[
        'http://localhost:8080/img/xmad_15548066591437_Stxlj.4151c4f8.jpg',
        'http://localhost:8080/img/xmad_15548890300924_zATjN.9ad18307.jpg',
        'http://localhost:8080/img/xmad_15562437458804_IuNaE.9ceeb890.jpg',
        'http://localhost:8080/img/xmad_15562619007912_lsyzN.d1537e2c.jpg',
        'http://localhost:8080/img/xmad_1556276298162_jhDIr.ae3e31d6.jpg'
      ]
    }
  },
  methods: {
    lastPage(){
     
     if(this.num==0){
       this.num=this.imgs.length-1;
      }else{
       this.num--;
      }
      console.log('lastPage',this.num);
    },
    nextPage(){
      
      if(this.num==4){
       this.num=0;
      }else{
       this.num++;
      }
      console.log('nextPage',this.num);
    }
  },
  mounted() {
   setInterval(()=>{
    if(this.num==4){
      this.num=0;
    }else{
      this.num++;
    }
   },3000);
  }
};
</script>

<style scoped>
#M-main-container {
  display: flex;
  flex-direction: column;
  width: 1226px;
  margin: 0 auto;
  padding: 0;
}
.site-header {
  display: flex;
  justify-content: space-between;
  height: 55px;
  width: 100%;
  margin: 30px auto;
}
.site-header-logo {
  width: 55px;
  height: 55px;
  background-image: url("../assets/img/img.png");
  background-position: 55px, 0;
  transition: all 0.3s;
  overflow: hidden;
}
.site-header-logo:hover {
  background-position: 0px, 0;
}
.site-header-content-ul li {
  display: inline-block;
  margin-right: 20px;
  text-align: center;
  line-height: 55px;
}

.site-header-content-ul li:hover {
  color: #fd6310;
}
.site-header-search {
  width: 370px;
  height: 100%;
}
.site-header-search {
  display: flex;
  justify-content: center;
  align-items: center;
}

.site-content {
  display: flex;
  width: 1228px;
}
.site-content-left {
  width: 290px;
  height: 535px;
  background-color: #4e8b84;
  box-sizing: border-box;
}
.site-content-left-ul {
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  padding: 25px 0 25px 0;
}
.site-content-left-ul-li {
  display: flex;
  justify-content: space-between;
  height: 50px;
  width: 100%;
  padding: 0 25px 0 35px;
  margin: 0;
  box-sizing: border-box;
  line-height: 50px;
}
.site-content-left-ul-li:hover {
  color: #fff;
  background-color: #fd6310;
}
.site-content-left-ul-li-icon {
  display: flex;
  align-items: center;
  justify-content: center;
}

.site-content-right {
  position: relative;
  width: 900px;
  height: 100%;
}
.site-content-right img {
  width: 937px;
  height: 535px;
  /* display: none; */
}
.site-content-right .current{
  display: block;
}

.site-content-right-button-left{
  position: absolute;
  left: 0;
  top: 50%;
  width: 20px;
  height: 20px;
  transform: translateY(50%);
  z-index: 10;
}
.site-content-right-button-right{
  position: absolute;
  right: 0;
  top: 50%;
  width: 20px;
  height: 20px;
  transform: translateY(50%);
  z-index: 10;
}
.site-content-right-index{
  position: absolute;
  right: 2%;
  bottom: 5%;
}
.site-content-right-index div{
  display: inline-block;
  width: 15px;
  height: 15px;
  margin-right: 15px;
  border-radius: 50%;
  z-index: 10;
  background: #fd6310
}
.current-index{
  /* background-color: aquamarine; */
  transform: scale(1.2);
  z-index: 2;
}

.site-footer{
  display: flex;
  width: 100%;
  height: 213px;
  margin-top: 20px;
}

.site-footer-left{
  display: flex;
  flex-wrap: wrap;
  width: 290px;
  height: 100%;
  background-color: #5f5750;
  opacity: 0.7;
  font-size: 14px;
}
.site-footer-left-item:hover{
  color: #fff;
}

.site-footer-left-item{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: 50%;
  width: 33.3%;
}
.site-footer-right1,.site-footer-right2,.site-footer-right3{
  width: 300px;
  height: 100%;
  margin-left:13px; 
}
.site-footer-right1 img,.site-footer-right2 img,.site-footer-right3 img{
  width: 100%;
  height:100%;
}
</style>