# phoneView
PhoneView是一个查看手机基本信息(软硬件)的Android小程序，结合MaterialViewPager实现MD风格化，可以作为入门程序练手～

[MaterialViewPager](https://github.com/florent37/MaterialViewPager)可以从网络或者本地加载tab的背景图片，并且可以实现图片缓慢移动的伪动画效果，是一个非常好用的库
<img src="https://github.com/henan715/phoneView/blob/master/1.png" width="30%" height="30%">
<img src="https://github.com/henan715/phoneView/blob/master/2.png" width="30%" height="30%">
<img src="https://github.com/henan715/phoneView/blob/master/3.png" width="30%" height="30%">
<img src="https://github.com/henan715/phoneView/blob/master/4.png" width="30%" height="30%">
<img src="https://github.com/henan715/phoneView/blob/master/5.png" width="30%" height="30%">

整个工程其实可以压缩成一个fragment+adapter+activity的形式，在滑动tab的时候加载数据，这样的话就可以省去每一个界面写一个fragment的繁琐，这边为了简洁起见，用这种比较粗糙的方法写了。

还有一个小问题：tab在滑动有些小瑕疵，待解决
