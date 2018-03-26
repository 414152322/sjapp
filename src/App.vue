<template>
  <div id="app">
    <img src="./assets/wzttop.jpg" class="imgtop">
    <router-view/>
    <navfooterview></navfooterview>
  </div>
</template>

<script>
import navfooter from "@/components/navfooter"
export default {
  name: 'App',
  components:{
      "navfooterview":navfooter
  }
}
</script>

<style>
body{ margin:0;padding:0; font-family: "微软雅黑",arial,"宋体","Lucida Grande",tahoma;background:#ffffff; min-width:320px;}
html{*overflow-y:auto;}
img{border:none;vertical-align:middle;}
a{color:#585757;text-decoration:none;font-family: "微软雅黑",arial,"宋体","Lucida Grande",tahoma;}
ul,li{list-style:none;}
h2{ color:#434343;}
ul,li,p,input,img,dl,dd,dt,h1,h2,h3,h4{ margin:0;padding:0; }
em,i{ font-style:normal}
.clear{ clear:both; height:0; font-size:0; line-height:0;}
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
.imgtop{ width: 100%}
</style>
