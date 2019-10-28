# 欢迎来到超级大哈克的个人购物网站！



<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <script src="../Public_Filter/study/js/jquery/2.0.0/jquery.min.js"></script>
    <link
      href="../Public_Filter/study/css/bootstrap/3.3.6/bootstrap.min.css"
      rel="stylesheet"
    />
    <script src="../Public_Filter/study/js/bootstrap/3.3.6/bootstrap.min.js"></script>
    <link rel="stylesheet" href="publicPage.css" />
    <title>天猫首页页面(陈健聪)</title>
  </head>

  <body>
    <!-- Nav页面 -->
    <nav class="top">
      <a href="http://www.chenjiancong.com/all-Page/index.html">
        <span class="glyphicon glyphicon glyphicon-home redColor"></span>
        <!--引用bootstrap图标-->
        天猫首页
      </a>
      <span>喵，欢迎来到天猫</span>
      <a href="../other-page/Login.html">请先登录</a>
      <a href="../other-page/register.html">免费注册</a>
      <span class="pull-right">
        <!--pull-right是bootstrap向右浮动的方法-->
        <a href="../Order-page/order.html">我的订单</a>
        <a href="../shopping-cart/cart.html">
          <span class="glyphicon glyphicon-shopping-cart redColor"></span>
          购物车<strong>0</strong>件</a
        >
      </span>
    </nav>

    <!-- Search搜索栏部分 -->
    <div class="search">
      <a href="#"
        ><img
          class="logo"
          id="logo"
          src="../Public_Filter/img/site/logo.gif"
          alt="天猫logo"
      /></a>
      <!--天猫logo标签-->
      <div class="searchDiv">
        <input type="text" placeholder="时尚男鞋 太阳帽" name="keyword" />
        <a href="../category-page/Sorting_Pricing.html">
          <button class="searchButton" type="submit">搜索</button>
        </a>
        <div class="searchBelow">
          <!--搜索栏底线部分-->
          <span><a href="#">平衡车</a><span>|</span></span>
          <span> <a href="#nowhere"> 扫地机器人 </a> <span>|</span> </span>
          <span> <a href="#nowhere"> 原汁机 </a> <span>|</span> </span>
          <span> <a href="#nowhere"> 冰箱 </a></span>
        </div>
      </div>
    </div>

    <!-- 嵌入html页面代码 -->
    <iframe
      src="../merge_lunbo_sort/merge.html"
      width="100%"
      height="550"
      frameborder="0"
      scrolling="no"
    >
      <a href="../merge_lunbo_sort/merge.html"
        >你的浏览器不支持iframe页面嵌套，请点击这里访问页面内容。</a
      >
    </iframe>
    <!-- 嵌入html页面代码 -->
    <iframe
      src="../homePage-Product_list/producelist.html"
      width="100%"
      height="1630"
      frameborder="0"
      scrolling="no"
    >
      <a href="../homePage-Product_list/producelist.html"
        >你的浏览器不支持iframe页面嵌套，请点击这里访问页面内容。</a
      >
    </iframe>

    <!-- footer页脚部分 -->

    <div class="footer" id="footer">
      <!--页脚顶部图片-->
      <div class="footer_img">
        <a href="#">
          <img src="../Public_Filter/img/site/ensure.png" alt="" />
        </a>
      </div>
      <!--页脚中部文字描述-->
      <div class="footer_desc">
        <!--1-->
        <div class="descColumn">
          <span class="descColumnTitle">购物指南</span>
          <a href="#nowhere">免费注册</a>
          <a href="#nowhere">开通支付宝</a>
          <a href="#nowhere">支付宝充值</a>
        </div>
        <!--2-->
        <div class="descColumn">
          <span class="descColumnTitle">天猫保障</span>
          <a href="#nowhere">发票保障</a>
          <a href="#nowhere">售后规则</a>
          <a href="#nowhere">缺货赔付</a>
        </div>
        <!--3-->
        <div class="descColumn">
          <span class="descColumnTitle">支付方式</span>
          <a href="#nowhere">快捷支付</a>
          <a href="#nowhere">信用卡</a>
          <a href="#nowhere">蚂蚁花呗</a>
          <a href="#nowhere">货到付款</a>
        </div>
        <!--4-->
        <div class="descColumn">
          <span class="descColumnTitle">商家服务</span>
          <a href="#nowhere">商家入驻</a>
          <a href="#nowhere">商家中心</a>
          <a href="#nowhere">天猫智库</a>
          <a href="#nowhere">天猫规则</a>
          <a href="#nowhere">物流服务</a>
          <a href="#nowhere">喵言喵语</a>
          <a href="#nowhere">运营服务</a>
        </div>
        <!--5-->
        <div class="descColumn">
          <span class="descColumnTitle">手机天猫</span>
          <a href="#">
            <img src="../Public_Filter/img/site/ma.png" alt="" />
          </a>
        </div>
        <div style="clear:both"></div>
      </div>
      <!-- 页脚最底部信息栏 -->
      <div class="footer">
        <img src="../Public_Filter/img/site/cateye.png" class="cateye" alt="" />
        <!-- 底部页脚 -->
        <div class="copyright">
          <div class="white_link">
            <a href="#nowhere">关于天猫</a>
            <a href="#nowhere"> 帮助中心</a>
            <a href="#nowhere">开放平台</a>
            <a href="#nowhere"> 诚聘英才</a>
            <a href="#nowhere">联系我们</a>
            <a href="#nowhere">网站合作</a>
            <a href="#nowhere">法律声明</a>
            <a href="#nowhere">知识产权</a>
            <a href="#nowhere"> 廉正举报 </a>
          </div>
          <div class="white_link">
            <a href="#nowhere"> 阿里巴巴集团</a><span class="slash">|</span>
            <a href="#nowhere"> 淘宝网</a><span class="slash">|</span>
            <a href="#nowhere">天猫 </a><span class="slash">|</span>
            <a href="#nowhere"> 聚划算</a><span class="slash">|</span>
            <a href="#nowhere">全球速卖通</a><span class="slash">|</span>
            <a href="#nowhere">阿里巴巴国际交易市场</a
            ><span class="slash">|</span> <a href="#nowhere">1688</a
            ><span class="slash">|</span> <a href="#nowhere">阿里妈妈</a
            ><span class="slash">|</span> <a href="#nowhere"> 阿里旅行·去啊 </a
            ><span class="slash">|</span> <a href="#nowhere"> 阿里云计算 </a
            ><span class="slash">|</span> <a href="#nowhere"> 阿里通信 </a
            ><span class="slash">|</span> <a href="#nowhere"> YunOS </a
            ><span class="slash">|</span> <a href="#nowhere"> 阿里旅行·去啊 </a
            ><span class="slash">|</span> <a href="#nowhere"> 万网 </a
            ><span class="slash">|</span> <a href="#nowhere"> 高德 </a
            ><span class="slash">|</span> <a href="#nowhere"> 优视 </a
            ><span class="slash">|</span> <a href="#nowhere"> 友盟 </a
            ><span class="slash">|</span> <a href="#nowhere"> 虾米 </a
            ><span class="slash">|</span> <a href="#nowhere"> 天天动听 </a
            ><span class="slash">|</span> <a href="#nowhere"> 来往 </a
            ><span class="slash">|</span> <a href="#nowhere"> 钉钉 </a
            ><span class="slash">|</span>
            <a href="#nowhere"> 支付宝 </a>
          </div>
          <!--  -->
          <div class="license">
            <span>增值电信业务经营许可证： 浙B2-20110446</span>
            <span>网络文化经营许可证：浙网文[2015]0295-065号</span>
            <span>互联网医疗保健信息服务 审核同意书 浙卫网审【2014】6号 </span>
            <span>互联网药品信息服务资质证书编号：浙-（经营性）-2012-0005</span>
            <div class="copyRightYear">© 2003-2016 TMALL.COM 版权所有</div>
            <div>
              <img src="../Public_Filter/img/site/copyRight1.jpg" />
              <img src="../Public_Filter/img/site/copyRight2.jpg" />
            </div>
          </div>
        </div>
      </div>
    </div>
    
    
    <style>
    /* nav导航栏部分 */
body {
  font-size: 14px; /*天猫的字体都是14px*/
  font-family: arial;
}
.redColor {
  color: #c40000 !important; /*天猫红颜色， !important优先级最高*/
}
a {
  color: #999; /*天猫字体颜色*/
}
nav.top {
  background-color: #f2f2f2; /*导航栏背景颜色*/
  padding: 5px 0;
  border-bottom: 1px solid #e7e7e7; /*底部1像素边框*/
}
nav.top span,
nav.top a {
  color: #999;
  margin: 0 10px;
}
nav.top a:hover {
  color: #c40000;
  text-decoration: none;
}

/* Search搜索栏部分 */

.search a img{
margin:190px 70px 80px 120px;
}

.searchDiv {
  width: 400px; /*搜索栏的总长度*/
  background-color: #c40000;
  display: block; /*块元素展示*/
  height: 40px;
  margin: 50px auto; /*让搜索栏居中显示*/
  padding: 1px;
}

.searchDiv input {
  width: 275px;
  outline: none;
  height: 36px; /*搜索框的高度*/
  margin: 1px;
  border: transparent 1px solid;
}
.searchDiv button {
  border: transparent 1px solid;
  background-color: #c40000;
  width: 110px;
  color: white;
  font-size: 20px;
  font-weight: bold;
  outline: none; /*去掉搜索栏的边框*/
}
.searchBelow {
  margin-top: 3px;
  margin-left: -20px;
}
.searchBelow span,
a {
  color: #999;
}
.searchBelow a {
  margin: 0 20px;
  font-size: 14px;
}

.search .logo {
  position: absolute; /*图片使用绝对定位的方式，让图片和搜索栏div水平放置的效果*/
  left: 0;
  top: 30px;
  z-index: -1;
}
body {
  font-size: 12px;
  font-family: Arial;
}

.searchBelow a:hover {
  text-decoration: none;
  color: #c40000;
}

/* footer页脚部分 */
.footer {
  margin: 0;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #e7e7e7;
}

.footer_img {
  margin-top: 24px;
  margin-bottom: 24px;
  text-align: center;
  /* 图片居中 */
}

.footer_desc {
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #e7e7e7;
  padding-top: 30px;
  margin: 0 20px;
}

.footer_desc .descColumn {
  /* 购物指南，天猫保障等列 */
  /* 让每一块各占20% */
  width: 20%;
  float: left;
  /* 向左浮动，使这些列水平摆放 */
  text-align: center;
}
.descColumn span.descColumnTitle {
  /* 购物指南，天猫保障等字样 */
  color: #646464;
  font-weight: bold;
  font-size: 16px;
}

.descColumn a {
  display: block;
  padding-top: 3px;
  color: #999;
  text-decoration: none;
}

.descColumn a:hover {
  /* 鼠标悬停 */
  color: #c40000;
}

body {
  font-size: 14px;
  font-family: arial;
}

/* 最底部页脚部分 */

.copyright {
  background-color: black;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #c40000;
}
.copyright .white_link a {
  /* 页脚底部变成白色的超链 */
  color: white;
  padding: 0 5px;
  text-decoration: none;
}
.copyright .white_link a:hover {
  text-decoration: underline;
}
.copyright .white_link {
  /* 超链之间的间隔 */
  padding: 10px 0;
  margin-left: 15px;
}
.copyright .white_link .slash {
  color: white;
}

.license {
  /* 于经营许可证部分 */
  margin-left: 15px;
  padding-bottom: 30px;
}
.license span {
  color: #a4a4a4;
}
.license .copyRightYear {
  color: #686868;
  margin: 10px 0;
}
img.cateye {
  /* 猫耳朵图片 */
  margin-left: 30px;
}

    </style>
    
  </body>

  <script>
    $("a[href]").click(function() {
      var href = $(this).attr("href");
      if ("#nowhere" == href || "#" == href) {
        alert("很抱歉，站长在拼命开发中，此链接暂不可用 ┭┮﹏┭┮");
      }
    });
  </script>
</html>
