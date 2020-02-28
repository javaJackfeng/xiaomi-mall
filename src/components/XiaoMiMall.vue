<template>
 <el-container id="container">
   <el-header height='50px'>
    <Mheader></Mheader>
   </el-header>
   <el-main>
    <Mmain></Mmain>
    <FlashDeal/>
    <phone/>
    <HomeAppliances/>
    <intelligence/>
    <collocation/>
    <Surrounding/>
    <Video/>
   </el-main>
   <el-footer>
    <Mfooter/>
    <Link/>
   </el-footer>
 </el-container>
</template>

<script>
import Mheader from './M-header';
import Mmain from './M-main';
import FlashDeal from './FlashDeal';
import phone from './phone';
import HomeAppliances from './HomeAppliances';
import intelligence from './intelligence';
import collocation from './collocation';
import Surrounding from './Surrounding';
import Video  from './Video';
import Mfooter from './Mfooter';
import Link from './Link'
export default {
  name: 'XiaoMiMall',
  components:{
    Mheader,
    Mmain,
    FlashDeal,
    phone,
    HomeAppliances,
    intelligence,
    collocation,
    Surrounding,
    Video,
    Mfooter,
    Link
  }
}
</script>


<style >
header{
  background-color: #333333;
  padding: 0;
}
main{
  padding: 0;
}
</style>
