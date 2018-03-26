<template>
<div class="navfooter">
        <ul class="nav_footer">
         <li class="bianbeij">
               <a href="###">
               <span class="navf1"></span>
                 <span class="navfyem1">首页</span>
                 </a>
             </li>
             <li>
               <a href="###">
               <span class="navf2"></span>
                 <span class="navfyem1">排名</span>
                 </a>
             </li>
             <li>
               <a href="###">
               <span class="navf3"></span>
                 <span class="navfyem1">报名</span>
                 </a>
             </li>
             <li>
               <a href="###">
               <span class="navf4"></span>
                 <span class="navfyem1">参与奖</span>
                 </a>
             </li>
      </ul>
</div>
</template>

<script>
export default {
    name:"navfooter"
}
</script>

<style lang="css" scoped>
.nav_footer{ height:65px; background:url(../assets/bottomxia.jpg) repeat-x; width:100%; position:fixed; bottom:0; left:0;z-index: 999999;}
.nav_footer li{ overflow:hidden;float:left;width:25%; }
.nav_footer li a{ width:100%; height:65px; text-align:center; display:block;}
.nav_footer .bianbeij a{ background:url(../assets/bottomxia2.jpg) repeat-x;}
.nav_footer li span{ color:#f8f8f8; font-size:14px;}
.navfyem1{ width:100%; display:block; line-height:20px;}
.navf1{ background:url(../assets/nava1.png) no-repeat; width:24px; height:24px; display:inline-block; margin:9px 0 0 0;}
.navf2{ background:url(../assets/nava2.png) no-repeat; width:24px; height:24px; display:inline-block; margin:9px 0 0 0;}
.navf3{ background:url(../assets/nava3.png) no-repeat; width:24px; height:24px; display:inline-block; margin:9px 0 0 0;}
.navf4{ background:url(../assets/nava4.png) no-repeat; width:24px; height:24px; display:inline-block; margin:9px 0 0 0;}
</style>
