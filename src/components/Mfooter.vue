<template>
  <div id="container">
    <div id="container-content">
      <div class="container-content-top">
        <ul class="container-content-top-ul">
          <li class="container-content-top-ul-li">
            <i class="el-icon-refresh"></i>
            预约维修服务
          </li>
          <li class="container-content-top-ul-li">
            <i class="el-icon-refresh"></i>
            七天无理由退货
          </li>
          <li class="container-content-top-ul-li">
            <i class="el-icon-refresh"></i>
            15天免费换货
          </li>
          <li class="container-content-top-ul-li">
            <i class="el-icon-refresh"></i>
            满99元包邮
          </li>
          <li class="container-content-top-ul-li">
            <i class="el-icon-refresh"></i>
            520余家售后网点
          </li>
        </ul>
      </div>
      <div class="container-content-main">
        <div class="container-content-main-left">
          <dl class="col-links">
            <dt>帮助中心</dt>
            <dd>
              <a href>账号管理</a>
            </dd>
            <dd>
              <a href>购物指南</a>
            </dd>
            <dd>
              <a href>订单中心</a>
            </dd>
          </dl>
          <dl class="col-links">
            <dt>服务支持</dt>
            <dd>
              <a href>售后政策</a>
            </dd>
            <dd>
              <a href>自助服务</a>
            </dd>
            <dd>
              <a href>相关下载</a>
            </dd>
          </dl>
          <dl class="col-links">
            <dt>线下门店</dt>
            <dd>
              <a href>小米之家</a>
            </dd>
            <dd>
              <a href>服务网点</a>
            </dd>
            <dd>
              <a href>授权体验店</a>
            </dd>
          </dl>
          <dl class="col-links">
            <dt>关于小米</dt>
            <dd>
              <a href>了解小米</a>
            </dd>
            <dd>
              <a href>加入小米</a>
            </dd>
            <dd>
              <a href>投资者关系</a>
            </dd>
            <dd>
              <a href>廉正举报</a>
            </dd>
          </dl>
          <dl class="col-links">
            <dt>关注我们</dt>
            <dd>
              <a href>新浪微博</a>
            </dd>
            <dd>
              <a href>官方微信</a>
            </dd>
            <dd>
              <a href>联系我们</a>
            </dd>
          </dl>
          <dl class="col-links">
            <dt>特色服务</dt>
            <dd>
              <a href>F 码通道</a>
            </dd>
            <dd>
              <a href>礼物码</a>
            </dd>
            <dd>
              <a href>防伪查询</a>
            </dd>
          </dl>
        </div>
        <div class="container-content-main-right">
          <p class="phone">400-100-5768</p>
          <p>
            周一至周日 8:00-18:00
            <br />（仅收市话费）
          </p>
          <div class="btn-message">人工服务</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
#container {
  background-color: #fff;
  width: 100%;
}
#container-content {
  width: 1226px;
  margin: 0 auto;
}
.container-content-top {
  padding: 27px 0;
  border-bottom: 1px solid #e0e0e0;
}
.container-content-top-ul {
  display: flex;
  width: 100%;
}
.container-content-top-ul-li {
  display: inline-block;
  width: 19.8%;
  height: 25px;
  border-left: 1px solid #e0e0e0;
  line-height: 25px;
  text-align: center;
  font-size: 16px;
  color: #616161;
}
.container-content-top-ul-li:first-child {
  border-left: 0;
}
.container-content-top-ul-li:hover {
  color: #fd6310;
}
.container-content-main {
  display: flex;
  padding: 40px 0;
}
.container-content-main-left {
  display: flex;
  width: 80%;
}
.container-content-main-right {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 20%;
  height: 112px;
  border-left: 1px solid #e0e0e0;
  text-align: center;
  margin-left: auto;
  color: #616161;
}
.col-links {
  width: 160px;
  height: 112px;
  margin: 0;
}
dt {
  margin: -1px 0 26px;
  line-height: 1.25;
  font-size: 14px;
  color: #424242;
}
dd {
  margin: 10px 0 0;
  font-size: 12px;
}
dl a {
  text-decoration: none;
  font-size: 12px;
  color: #757575;
}
dl a:hover {
  color: #fd6310;
}
.phone {
  margin: 0 0 5px;
  font-size: 22px;
  line-height: 1;
  color: #ff6700;
}
.btn-message {
  border: 1px solid #f25807;
  margin-top: 16px;
  width: 50%;
  text-align: center;
  color: #f25807;
}
.btn-message:hover {
  color: #fff;
  background-color: #f25807;
  border-color: #f25807;
}
</style>