<template>
<div class="layout">
      <ul class="bm_tp_fwl">
            <li>
               <span class="bmw1">已报名</span>
                 <span class="bmw2">35698</span>
             </li>
             <li>
               <span class="bmw1">投票人次</span>
                 <span class="bmw2">1956842</span>
             </li>
             <li>
               <span class="bmw1">访问量</span>
                 <span class="bmw2">1956842</span>
             </li>
      </ul>
      <div class="inputkuang">
      		<input type="text" class="txtinp" value="请输入名字或者编号" onblur="if(this.value==''){this.value='请输入名字或者编号';}" onfocus="if(this.value=='请输入名字或者编号'){this.value=''}"/>
             <input type="submit" class="sbminp"  value="搜索"/>
      </div>

      <div class="cszp_tpph_qbm">
                 <p class="qiehuanxuanze">
                          <a href="###" class="bianse">最新参赛</a>
                          <a href="###">选手排名</a>
                 </p>
                 <playsview></playsview>
      </div>
</div>
</template>

<script>
import plays from "@/pages/player/plays"
export default {
    name:"layout",
    data(){
        return{

        }
    },
    components:{
      "playsview":plays
    }
}
</script>

<style lang="css" scoped>
/*已报名投票访问量*/
.bm_tp_fwl{ width:99%; height:69px; background:#3871b8; padding:13px 0 0 1%;}
.bm_tp_fwl li{ float:left; width:26.3%; height:54px; background:#ffffff; margin:0 0 0 5%;}
.bm_tp_fwl li span{ display:block; width:100%; text-align:center;}
.bmw1{ font-size:15px; color:#333333;margin: 7px 0 0; line-height:20px;}
.bmw2{ font-size:14px; color:#ff7e00; font-weight:bold; line-height:20px;}
/*姓名编号搜索*/
.inputkuang{ height:47px; width:78%; background:#226299;padding:13px 11% 0;}
.txtinp{ height:33px; line-height:33px; background:#ffffff; font-size:13px; color:#969696; font-family: "微软雅黑",arial,"宋体","Lucida Grande",tahoma; width:76%; padding:0 0 0 4%; border:none; float:left;}
.sbminp{ height:33px; line-height:29px; background:#ffa60b; font-size:14px; color:#ffffff; font-family: "微软雅黑",arial,"宋体","Lucida Grande",tahoma; width:20%; border:none; float:left; cursor:pointer;}
/*参赛作品投票排行前100名*/
.cszp_tpph_qbm{ background:#f2f2f2; padding:30px 0 7px 0; overflow:hidden;}
.qiehuanxuanze{ padding:0 6% 21px; overflow:hidden;}
.qiehuanxuanze a{ float:left; display:block; width:50%; height:36px; text-align:center; line-height:36px; background:#3871b8; color:#ffffff;font-size:14px;}
.qiehuanxuanze .bianse{ background:#ffa60b; font-weight:bold;}
</style>
