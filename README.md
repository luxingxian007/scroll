# scroll 视差效果
# 项目演示 [效果展示 Demo](http://luxingxian007.github.io/scroll/)
# 用法
## step1 html格式
~~~
  <br />
	<br />
	<div class="scroll_img"> this is img</div>
	<br />
	<br />
	<br />

	<div class="scroll_img sc2"> this is img s2</div>
	<br />
	<br />
	<br />
	<br />
	<div class="scroll_img sc3"> this is img S3</div>
	<br />
	<br />
	<br />
	<br />
	<br />
~~~
## css 格式
~~~
.scroll_img{ height: 400px; line-height: 400px; font-size: 100px; background:url(images/BG1.jpg); color: #fff; margin-top:250px; text-align: center; text-shadow:0 3px 2px #625351; font-family:"microsoft yahei";}
.sc2{ background-image:url(images/BG2.jpg);}
.sc3{ background-image:url(images/BG3.jpg);}
~~~
## 引用jQuery
~~~
<script src="jquery/jquery-1.4.2.min.js"></script>
~~~
