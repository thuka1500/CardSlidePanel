android-card-slide-panel
child-views can be slided to the horizontal edge of the screen and reborn without creating new views
### 序言
故事的起点是这样的-<br>
* 有一个技术讨论的QQ群，里面活跃着一群技术牛人。他们编码一流，飞天遁地，无所不能。他们知道你所不知的技术，玩过你没有玩过的App。<br>
* 在一个月高风黑的晚上，一个素未谋面的大侠说：“探探”app做的甚好，滑动流畅，阴影效果32个赞。致敬经典，怀着崇拜之情，我偷偷下载了这个app，然后在四下无人的时候，注册了账号。我打开了app。<br>
* 确实惊艳至极，实至名归！卡片式的交互体验，是一种新的创新！曾几何时，有一位兄台说过：“boss直聘”app的“每日推荐”左右滑动效果略屌。当时我也下载了，安装了，注册了，还被公司HR发现了。只是当时，感觉ui有点小卡（不要打我，我怕疼）。<br>
* 时过境迁，“探探”摆在眼前，我知道ViewDragHelper到底能有多牛逼了。终于，我下定了决心要做好这个project。请看图:<br>

### 截图
<td>
	 <img src="capture01.gif" width="300" height="500" />
	 <img src="capture03.gif" width="300" height="500" />
</td>

### 正经一点
不得不说，探探的ui效果真的很赞。在着手这个project之前，我没有参考过github上其它类似的开源项目。所以，如果这个project重复造了轮子，请不要打我。<br>
其实，我之前有一个开源工程叫android-image-slide-panel，多多少少跟这个工程有些类似。由于有了之前的积淀，所以从一开始，我就有了思路。只是在不断推进代码的过程中，遇到了一些问题。<br>
如果我能不要脸一些，我会说这个项目的优点是：<br>
* 快。滑动很流畅，不信你打我！<br>
* 高效。仅仅四个卡片view轻松搞定任意多的数据。<br>
* 灵活。自定义ViewGroup对卡片view的高度实现了自适应。<br>
* 细节。卡片之间联动的视觉效果，是像素级的精确。<br>

模仿"探探"首页的卡片滑动效果，"boss直聘"也有类似的效果。
代码后面上传~
