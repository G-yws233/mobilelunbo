js基础语法

BOM
	获取屏幕尺寸
	window.innerWidth
	window.innerHeight

	获取浏览器宽高
	document.documentElement.clientWidth
	document.documentElement.clientHeight

	setInterval(回调函数，时间)
	setTimeout(回调函数，时间)

Dom
	document.getElementById()
	document.getElementByClassName()
	<!-- IE6-IE8不支持 -->
	document.getElementByTagName()

	document.getElementByName()
	

（IE8支持H5 不识别css3选择器）
  H5选择器
	document.querySelector()---一个元素
	document.queryAllSelector()---元素集合

  CSS3选择器
	select


	事件
	鼠标事件---onclick ondblclick onmouseover/out/move/up/down/leave

	键盘事件---onkeydown/up/press
	表单事件---onsubmit/onreset/onchange/onblur/onfocus
	页面事件---onload/DOMContentLoaded
				区别：onload--页面资源加载完成 内容+图片
					  	window.onload=function(){}
				      DOMContentLoaded--页面结构加载完成
				        window.addEventListener("DOMContentLoaded",function(){})

				以上两种加载方式：图片高度获取不到


	内容操作：innerHTML、innerText、textContent

	属性 样式
		标准属性  div: class id style title contenteditabled
				    a: href target contenteditabled
				  img: alt src class id style title contenteditabled
		操作样式
		获取样式：box.currentStyle()
				  getComputedStyle(obj对象,null)[style属性];

	事件驱动：事件 事件源 事件处理程序
	事件对象
	阻止流浪器默认行为

js兼容函数库


麦考林官网

选项卡
轮播图 左右箭头 下标
楼层跳转
按需加载
下拉菜单
放大镜
拖拽


触摸事件：
		ontouchstart---当手指触摸屏幕的时候触发，即使已经有一个手指放在屏幕上也会触发
		 ontouchmove---当手指在屏幕上滑动时连续触发
		  ontouchend---当手指从屏幕上离开的时候触发
	   ontouchcancle---

-touches:当前位于屏幕上的所有手指的一个列表】
-targetTouches：特定于事件目标的Touch对象的数组。[当前手指]
-changeTouches：表示上次触摸以来发生了什么改变的Touches对象的数组。


0 : touch
-clientX：触目目标在视口中的x坐标。
-clientY：触目目标在视口中的y坐标。
-identifier：标示触目的唯一ID。
-pageX：触摸目标在页面中的x坐标。
-pageY：触摸目标在页面中的y坐标。
-screenX：触摸目标在屏幕中的x坐标。
-screenY：触摸目标在屏幕中的y坐标。
-target：触目的DOM节点目标






github


git pull 从服务器更新到本地

创建新分支
	git branch 分支名
查看分支
	git checkout 分支名
提交到指定分支
	git push origin 分支名