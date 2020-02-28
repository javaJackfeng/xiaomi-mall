<template lang="">
  <div class="header-container">
    <ul class="ul-left">
      <li>
        <a>小米商城</a>
      </li>
      <li>
        <a>MIUI</a>
      </li>
      <li>
        <a>ioT</a>
      </li>
      <li>
        <a>云服务</a>
      </li>
      <li>
        <a>金融</a>
      </li>
      <li>
        <a>有品</a>
      </li>
      <li>
        <a>小艾开发平台</a>
      </li>
      <li>
        <a>企业团购</a>
      </li>
      <li>
        <a>资质证照</a>
      </li>
      <li>
        <a>协议规则</a>
      </li>
      <li>
        <a>下载app</a>
      </li>
      <li>
        <a>Select location</a>
      </li>
    </ul>
    <div class="ul-right">
      <div>
        <a>登陆</a>
      </div>
      <div>
        <a>注册</a>
      </div>
      <div>
        <a>消息通知</a>
      </div>
      <div>
      <a>
        <i class='el-icon-shopping-cart-2' style='margin-right:3px'></i>
        <span>购物车(0)</span>
      </a>
    </div>
    </div>
    
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.header-container {
  display: flex;
  justify-content: space-between;
  width: 1226px;
  margin-left: auto;
  margin-right: auto;
  font-size: 12px;
}
.ul-left li,.ul-right div{
  display: inline-block;
  margin-right: 20px;
  line-height: 50px;
  text-align: center;
  color: #b0b0b0;
  list-style: none;
}
a:hover {
  color: #fff;
  text-decoration: none;
}
.ul-right{
  display: flex;
}
.ul-right div:last-child{
  background-color: #424242;
   font-size: 16px;
  padding-left: 20px;
  padding-right: 20px;
}

.ul-right div:last-child:hover,.ul-right div:last-child a:hover{
  background-color: #fff;
  color: #ff6700;
}

</style>