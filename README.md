# FriendCircle
##一起来撸个朋友圈吧(重构版)

欢迎来到本项目，这个项目是一个尝试性项目，目的在于从无到有撸出一个微信朋友圈。</br>

ps:所有最新进度基本都会先push到[main-dev](https://github.com/razerdp/FriendCircle/tree/main-dev)分支哦

#####【简略更新日志】
 - 2017/03/08
    + 解决浏览大图失败无法返回退出的问题[#41](https://github.com/razerdp/FriendCircle/issues/41)

 - 2017/03/02
    + 增加popup

 - 2017/03/01
    + UI微调
    + 发布朋友圈动态的activity预添加
    + TitleBarView稍作调整

 - 2017/02/28
    + 优化刷新icon的逻辑
    + 双击回顶部刷新

 - 2017/02/21
    + 标题栏整合到控件中
    + 预留发朋友圈的开关
    + 双击回到顶部

 - 更多日志请看 → [更新日志](https://github.com/razerdp/FriendCircle/blob/master/UPDATE_LOG.md)

---

**本项目的一切实现思路以及逻辑都有记录，它们都有在我的简书文集记载：**

[代码实现逻辑（简书合集）](http://www.jianshu.com/notebooks/3224048/latest)


##2017-02-08
重构后的朋友圈图片浏览过渡动画完成！（代码解析可能要等上几天）

代码解析地址：

待写

图片预览：

![](https://github.com/razerdp/FriendCirclePreview/blob/master/img/2017-02-08%E5%9B%BE%E7%89%87%E9%80%80%E5%87%BA%E5%8A%A8%E7%94%BB.gif)

***

####如果您遇到popup的导入失败，请在工程的gradle（不是app的gradle哦）加上这句话：

```xml
	allprojects {
		repositories {
			...
			maven { url "https://jitpack.io" }
		}
	}
```


#####关于作者我:
普普通通的安卓开发者一枚。

#####关于项目：
本项目意在按照我的经验弄出一个微信朋友圈，也许无法完全实现，但高仿应该是没问题的，只是时间问题←_←。

本项目于2016/12/01 全面覆盖master分支

本项目于2016/10/26 全面重构

本项目于2016/03/17 更改为mvp架构



本项目在更新的同时也会同步发布经验心得（撸代码的过程），不过因为在下才学疏浅，有些地方肯定做的不好，所以衷心希望如果您有好的建议或优化方案，可以留下脚印。


如果您愿意捐助一下项目，可以通过微信捐助哟~

![](https://github.com/razerdp/FriendCircle/blob/main-dev/wechat.jpg)



##LICENSE：
***
[MIT](https://github.com/razerdp/FriendCircle/blob/master/LICENSE)
