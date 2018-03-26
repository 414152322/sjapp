<template>
  <div class="plays">
      <section id="wrapper">
          <div id="container">
              <!--zhaoping-->
                    <div class="grid">
                        <div class="gridlimian">
                          <a href="###" style="display:block;"><img src="@/assets/imgtu1.jpg" width="100%" /></a>
                            <a href="###" class="toutayipiao">投他/她一票</a>
                            <div class="imgholder">1235票</div>
                            <div class="meta">
                                    <p>林妙可</p>
                                    <p>1029238号</p>
                             </div>
                        </div>
                    </div>
                <!--zhaoping-->
                <!--zhaoping-->
                      <div class="grid">
                          <div class="gridlimian">
                            <a href="###" style="display:block;"><img src="@/assets/imgtu1.jpg" width="100%" /></a>
                              <a href="###" class="toutayipiao">投他/她一票</a>
                              <div class="imgholder">1235票</div>
                              <div class="meta">
                                      <p>林妙可</p>
                                      <p>1029238号</p>
                               </div>
                          </div>
                      </div>
                  <!--zhaoping-->
                  <!--zhaoping-->
                        <div class="grid">
                            <div class="gridlimian">
                              <a href="###" style="display:block;"><img src="@/assets/imgtu1.jpg" width="100%" /></a>
                                <a href="###" class="toutayipiao">投他/她一票</a>
                                <div class="imgholder">1235票</div>
                                <div class="meta">
                                        <p>林妙可</p>
                                        <p>1029238号</p>
                                 </div>
                            </div>
                        </div>
                    <!--zhaoping-->
          </div>
      </section>
  </div>
</template>

<script>
import $ from 'jquery'
export default {
    name:"plays"
}
</script>

<style lang="css" scoped>
/*作品列表*/
#wrapper{
	 background:#f2f2f2;padding:0 5px 0;
}
#wrapper hgroup{
	text-align:center;
}
.grid h2{
	margin:11px 0;
	color:#333333;
	/*text-shadow:1px 1px 2px #A50031;*/
	font-size:18px; font-weight:normal;
	font-family:Arial Narrow, Arial, sans-serif;
}
.grid p{
	color:#777777;
	font-size:13px; line-height:22px;
}
#wrapper h3{
	font-style:italic;
	font-weight:normal;
	font-size:18px;
	text-shadow:1px 1px 0 #fff;
	color:#888;
	margin:5px 0;
}

#container{
	position:relative;
	margin:0 auto 25px;
	 background:#f2f2f2;width:100%;

}
.grid{
	width:300px;
	min-height:100px;
	background:#3871b8;
	margin:0 8px 3px 8px;
	font-size:12px;
	float:left;
	/*box-shadow: 0 1px 3px rgba(34,25,25,0.4);
	-moz-box-shadow: 0 1px 3px rgba(34,25,25,0.4);
	-webkit-box-shadow: 0 1px 3px rgba(34,25,25,0.4);*/

	-webkit-transition: top 1s ease, left 1s ease;
	-moz-transition: top 1s ease, left 1s ease;
	-o-transition: top 1s ease, left 1s ease;
	-ms-transition: top 1s ease, left 1s ease;
}

.meta{ margin: 9px 0 0; height:47px;}
.meta p{ color:#ffffff; line-height:18px;padding: 0 0 0 13px;}

.grid strong {
	line-height:26px;
	display:block;
	font-size:24px;
	color:#333333; font-weight:normal;
	}
.grid .meta{
	color:#333333;
}
.grid .imgholder img{
	max-width:100%;
	background:#ccc;
	display:block;
}
.gridlimian{ position:relative;}
.imgholder{  width:98px; height:62px; line-height:60px; text-align:right; font-size:18px; font-weight:bold; color:#ffffff;font-family:Arial Narrow, Arial, sans-serif; position:absolute; right:-5px; bottom:0; padding:0 17px 0 0;}
.imgholder span{ font-size:14px;}
.toutayipiao{ height:36px; background:#ffa60b;display:block;; line-height:34px; display:block; text-align:center; font-size:14px; font-weight:bold; color:#ffffff;}
@media screen and (max-width : 1240px) {
	body{
		overflow:auto;
	}
}
@media screen and (max-width : 900px) {
	#backlinks{
		float:none;
		clear:both;
	}
	#backlinks a{
		display:inline-block;
		padding-right:20px;
	}
	#wrapper{
	}
}
</style>
