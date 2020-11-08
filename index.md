<!DOCTYPE html>
<html>
<head>
	<title>qingqing's blogs</title>
</head>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>

<script>
$(document).ready(function(){
	$("#about").hover(function(){
		$("#hoverContent").html("<div style=\"font-size:24px\">\
					<li class=\"word1\"> \
						一個無聊時喜歡做烘培的女子 \
						<img src=\"https://i.imgur.com/E8YhXQa.jpg\"welght = \"300\" height=\"300\"> \
					</li>\
					<li>最愛的甜食--布朗尼😁😁</li> \
				</div> \
		");},
		function(){
			$("#hoverContent").html("");
		}
	);


	$("#record").hover(function(){
		$("#hoverContent").html("<br><img src=\"https://i.imgur.com/JY21FWi.jpg\" title=\"第一次用平底鍋烤麵包\" width=\"250px\" height=\"250px\" style=\"border-radius:10px\">\
						<img src=\"https://i.imgur.com/3mQEmDg.jpg\" title=\"裡面是水滴巧克力\" width=\"250px\" height=\"250px\" style=\"border-radius:10px\">\
						<img src=\"https://i.imgur.com/XeKVPCy.jpg\" title=\"用烤箱烤麵包，比平底鍋難一點點\" width=\"250px\" height=\"250px\"style=\"border-radius:10px\">\
					</br>\
						<img src=\"https://i.imgur.com/bHBYUJ3.jpg\" title=\"製作生吐司，還蠻簡單的，但比一班吐司還要難一點點\" width=\"250px\" height=\"250px\"style=\"border-radius:10px\">\
						<img src=\"https://i.imgur.com/CPnWe8i.jpg\" title=\"練習用烤箱烤麵包\" width=\"250px\" height=\"250px\"style=\"border-radius:10px\">\
						<img src=\"https://i.imgur.com/FPTWki4.jpg\" title=\"杯子蛋糕 + 玩擠花袋，擠花袋好難喔\" width=\"250px\" height=\"250px\"style=\"border-radius:10px\">\
					<br>\
						<img src=\"https://i.imgur.com/lxJVhiW.jpg\" title=\"水果塔，塔皮蠻像蛋塔的，內餡是卡士達醬，上面鋪滿了水果(但水果還蠻酸的)\" width=\"250px\" height=\"250px\"style=\"border-radius:10px\">\
						<img src=\"https://i.imgur.com/KJeQ4Ut.jpg\" title=\"巧克力戚風蛋糕，製作超級快，蠻簡單的，心血來潮最常製作的甜點\" width=\"250px\" height=\"250px\"style=\"border-radius:10px\">\
						<img src=\"https://i.imgur.com/3mwTFn5.jpg\" title=\"我最愛的布朗尼~製作也是超簡單，速度比戚風蛋糕更快，但就是有點甜，所以只有偶爾才會做\" width=\"250px\" height=\"250px\"style=\"border-radius:10px\">\
					</br>\"");},
		function(){
			$("#hoverContent").html("");
		});
	});
</script>

<style type="text/css">
	#title{
		color: #ffffff;
		font-family: Consolas;
		font-size:  100px;
		text-align: center;
	}

	#background_sourse{
		text-align: right;
		position: fixed; 
		bottom: 0; 
		right: 0;
	}

	#social{
		text-align: left;
		position: fixed; 
		bottom: 0; 
		left: : 0;
	}

	#sourse{
		color: #808080; 
		text-decoration: none;
	}

	#myBtn{
		
	}

	.multi_bg_example {
	  background-image : url(https://mdn.mozillademos.org/files/11305/firefox.png),
	                     url(https://mdn.mozillademos.org/files/11307/bubbles.png),
	                     linear-gradient(to right, rgba(30, 75, 115, 1),  rgba(255, 255, 255, 0));

	  background-repeat: no-repeat,
	                     no-repeat,
	                     no-repeat;

	  background-position: bottom right,
	                       left,
	                       right;
	}

	#container {

		color: white;
		font-family: Consolas;
        position: relative;
        text-align: left;
        width: 1250px;
        height: 500px;
        padding: 0px 0px 1300px 0px;
        margin: 0px auto;
		background: rgba(255, 171, 133,0.7);

	}

	#list{
		color: white;
        position: absolute;
        right: 0px;
        text-align: center;
        width: 400px;
        font-size: 3em;
        padding: 0px 0px 0px 0px;
        margin: 0px auto;		
	}

	.introduce{
		color: white;
        position: absolute;
        left: 50px;
        width: 600px;
        height: 1000px;
        padding: 75px 50px 0px 0px;
        margin: 0px auto;
		font-size: 3em;
		z-index: 9999;		
	}

	.photo{
		color: white;
        position: absolute;
        left: 50px;
        width: 500px;
        padding: 135px 50px 0px 0px;
        margin: 0px auto;
	}

	.word{
		width: 1300px;
		color: #fff;
		font-size: 3em;
	}

	.word1{
		color: #fff;
		position: : absolute;
		vertical-align: top;

	}
	
	#hoverContent{
		display: inline;
		position: relative;
	}

</style>

<body bgcolor="#000000" background = "https://i.imgur.com/OvpZ3Mg.gif" >
	<h1 id = "title">WELCOME TO MY BLOG</h1>

	<div id = "container">
	
		<marquee onMouseOver="this.stop()" onMouseOut="this.start()" style="margin:0px;opacity:0.75;" margin:20px scrollamount="10"  noshade width="100%">❤️🧡💛💚💙💜🤎🖤🤍❤️🧡💛💚💙💜🤎🖤🤍❤️🧡💛💚💙💜🤎🖤🤍❤️🧡💛💚💙💜🤎🖤🤍❤️🧡💛💚💙💜🤎🖤🤍❤️🧡💛💚💙💜🤎🖤🤍❤️🧡💛💚💙💜🤎🖤🤍❤️🧡💛💚💙💜🤎🖤🤍❤️🧡💛💚💙💜🤎🖤🤍❤️🧡💛💚💙💜🤎🖤🤍❤️🧡💛💚💙💜🤎🖤🤍❤️🧡💛💚💙💜🤎🖤🤍❤️🧡💛💚💙💜🤎🖤🤍❤️🧡💛💚💙💜🤎🖤🤍❤️🧡💛💚💙💜🤎🖤🤍❤️🧡💛💚💙💜🤎🖤🤍❤️🧡💛💚💙💜🤎🖤🤍❤️🧡💛💚💙💜🤎🖤🤍❤️🧡💛💚💙💜🤎🖤🤍❤️🧡💛💚💙💜🤎🖤🤍</marquee>

		<form>
			<div id="list">
			    <h3>無聊小表單</h3>
			    <p><input type="text" name="name" style="font-size:24px" placeholder="你的名字(or 綽號)" ></p>
			    <p><textarea rows="6" cols="21" style="font-size:24px" placeholder="許願清單"></textarea></p>
			    <script language="javascript">
					function submmit() {
					　alert("雖然我也看不到🤣🤣🤣🤣");
					}
				</script>
				<button onclick="submmit()" style="font-size:20px">送出資料</button>
			</div>
		</form>

		<div class="introduce">
			<span id="about">About Me</span> 
			<br>
			<span id="record">烘焙記錄</span> 
		</div>			

		<div class="photo word">
			<div id="hoverContent"></div>
		</div>
		
	</div>

	<div id="social">
		<a href="https://www.facebook.com/profile.php?id=100002777360057"><img src="https://i.imgur.com/XtL4oQ9.png " weight = "40" height = "40"></a> 
		<a href="https://www.instagram.com/qingqing_1015/"><img src="https://i.imgur.com/SyrMjHU.png"weight = "40" height = "40"></a> 
	</div>

	<div id = "background_sourse">
		<a id = "sourse" href="http://classic-album.udn.com/photo/play.jsp?uid=serena7376&f_BOOK_ID=379089&o=tt">背景來源</a>
	</div>
</body>
</html>
