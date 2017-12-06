# webApp-slider-widget
a webAPP demo


移动div的实现虽然可以使用position:absolute,但还是建议使用translate3d,因为可以启动手机的GPU加速，加速图片的渲染


-webkit-transform: translate3d(0px,0,0);

手指触摸屏幕touchstart
手指点击屏幕touchmove
手指抬起事件touchend

translate3d(x,y,z)
x:表示在x轴方向的位移。
y:表示在y轴方向的位移。
z:表示在z轴方向的位移
<mata name="viewpoint" conten="device-width",   //宽度等于设备的宽度
initial-scale=1.0,//默认放大倍数1.0
maximum-scale=1.0,//最大放大倍数1.0
minimum-scale=1.0,//最小放大倍数1.0（避免失误操作）
<meta name="apple-mobile-web-app-status-bar-style" content="black" ></mata>//IOS浏览器滚动条颜色
user-scalable=no"/>//禁止用户缩放
<meta name="apple-touch-fullscreen" content="YES" />//允许全屏应用

#### 要使得body占满全屏 
body{
 height:100%;
 position:absolute; // 耗内存

}



<ul>
	<li>
		<img width="320" src="1.jpg">
	</li>

</ul>

#### 图片上下居中显示
居中(高级浏览器)：
1、li{display:table-cell;vertical-align:middle;}
2、li{display:-webkit-box;-webkit-box-pack:center;-webkit-box-align:center;}
居中(一般)：
li{line-height:568px;vertical-align:middle;}
li img{vertical-align:middle;}


//根据窗口的比例与图片的比例来确定
//图片是根据宽度来等比缩放还是根据高度来等比缩放