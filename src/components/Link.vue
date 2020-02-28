<template>
  <div id="Container">
    <div id="Content">
      <div class="content-logo">
        <img src="../assets/img/house.png" alt />
      </div>
      <div class="link-content-main">
        <ul class="ui-link">
          <li class="li-link">小米商城 |</li>
          <li class="li-link">MIUI |</li>
          <li class="li-link">米家 |</li>
          <li class="li-link">米聊 |</li>
          <li class="li-link">多看 |</li>
          <li class="li-link">游戏 |</li>
          <li class="li-link">政企服务 |</li>
          <li class="li-link">小米天猫店 |</li>
          <li class="li-link">小米集团隐私政策 |</li>
          <li class="li-link">小米公司儿童信息保护规则 |</li>
          <li class="li-link">小米商城隐私政策 |</li>
          <li class="li-link">小米商城用户协议 |</li>
          <li class="li-link">问题反馈 |</li>
          <li class="li-link">Select Location</li>
        </ul>
        <p>
          © 京ICP证110507号 京ICP备10046444号 京公网安备11010802020134号 京网文[2020]0276-042号
          <br />（京）网械平台备字（2018）第00005号 互联网药品信息服务资格证 (京)-非经营性-2014-0090 营业执照 医疗器械质量公告
          <br />增值电信业务许可证 网络食品经营备案（京）【2018】WLSPJYBAHF-12 食品经营许可证
          <br />违法和不良信息举报电话：185-0130-1238 知识产权侵权投诉 本网站所列数据，除特殊说明，所有数据均出自我司实验室测试
        </p>
      </div>
      <div class="link-content-link-logo">
        <img src="//i1.mifile.cn/f/i/17/site/truste.png" alt />
        <img src="//s01.mifile.cn/i/v-logo-2.png" alt />
        <img src="//s01.mifile.cn/i/v-logo-1.png" alt />
        <img src="//i8.mifile.cn/b2c-mimall-media/ba10428a4f9495ac310fd0b5e0cf8370.png" alt />
      </div>
      <div class="footer-logo"></div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
#Container {
  background-color: #f5f5f5;
  width: 100%;
}
#Content {
  position: relative;
  width: 1226px;
  margin: 0 auto;
  padding-top: 20px;
}
.content-logo {
  position: absolute;
  width: 57px;
  height: 57px;
}
.link-content-main {
  display: absolute;
  color: #b0b0b0;
  padding-left: 67px;
}
.link-content-main p {
  font-size: 12px;
}
.li-link {
  display: inline-block;
  padding-left: 3px;
  color: #757575;
  font-size: 12px;
}
.li-link:first-child {
  border: 0;
}
.link-content-link-logo {
  display: flex;
  height: 28px;
  margin: 4px 0 0;
  padding-left: 67px;
}
.link-content-link-logo img {
  width: auto;
  height: 28px;
  margin-left: 0;
  margin-bottom: 15px;
}
.footer-logo {
  clear: both;
  margin: 30px auto 0;
  width: 267px;
  height: 19px;
  background: url(//s02.mifile.cn/assets/static/image/slogan2016.png) no-repeat
    center 0;
  padding-bottom: 30px;
}
</style>