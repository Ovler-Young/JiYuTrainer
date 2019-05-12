<p align="center">
  <a href="#">
    <img alt="JiYu Trainer" src="https://raw.githubusercontent.com/717021/JiYuTrainer/master/JiYuTrainerLogo256.png" width="128">
  </a>
</p>
<p align="center">
  <img alt="JiYu Trainer Title" src="https://raw.githubusercontent.com/717021/JiYuTrainer/master/JiYuTrainerTitle.png" width="128">
</p>
<p align="center">不再被极域电子教室控制</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/language-C++-blue.svg"></a>
  <a href="https://github.com/717021/JiYuTrainer/releases"><img src="https://img.shields.io/badge/version-1.6-greeb.svg"></a>
  <a href="https://github.com/717021/JiYuTrainer/blob/master/LICENSE"><img src="https://img.shields.io/badge/liscence-MIT-orange.svg"></a>
</p>

---

简介
---

本软件研发目的就是为了对抗极域电子教室，如果您的学校机房使用极域电子教室来控制学生电脑的话，本软件很可能会帮到你。

> 师讲课无聊啰嗦缓慢？想自己试试操作，却被该死的全屏广播控制，什么都不能干？拔掉网线后虽然自由了但是又看不到老师的演示了？

如果你被以上问题困扰，本软件可能是您非常想要的。

这是一个可以使 **极域电子教室全屏广播失效** 的软件，也就是说，在被老师全屏广播时，你不仅可以自由操作电脑，也还可以看老师的演示，自由+学习两不误，这不是很爽的事情吗？其还可以防止被老师控制（有点狠），以及自动关闭 “**黑屏安静**” 这种东西；由于本软件是将全屏调整为窗口，因此老师并不会发现你断线或是进行了非法操作。

当然，如果你是学渣，使用本软件只是只是为了想上课自己玩，那我不建议你使用本软件，更不建议你在别的同学面前用本软件装逼（有的人会这样做），本软件开发的初衷是为了一些理解能力强的、学习快的学生可以自己边看边操作，而不是被老师全屏广播控制而无聊，浪费时间。**并不是为了脱离老师控制而自己在课堂上不听老师讲课，想玩什么就玩什么**，总之了，这就是一个软件，得看使用的人怎么使用，**当然，我还是希望每个使用它的人都用在学习上**。

# 直接下载：

[下载软件最新版](https://github.com/717021/JiYuTrainer/blob/master/Release/JiYuTrainer.exe) 
[备用地址](http://update.imyzc.com/JiYuTrainer/files/JiYuTrainer.exe) 

![软件主要界面](https://raw.githubusercontent.com/717021/JiYuTrainer/master/ScreenShots.png)

# 操作方法

本软件专为小白设计，默认情况下，您不需要修改任何参数，直接运行exe，并最小化即可，软件会自动进行操作。

> 附加说明：本软件不依赖任何运行库，您只需复制一个 **JiYuTrainer.exe** 至目标电脑即可运行，本软件已将需要的DLL打包，它会自动进行安装。 **由于本软件会对极域电子教室进行操作，某些杀毒软件可能会报毒，您可能需要关闭杀毒软件或添加白名单**。

# 软件源码

编译以及生成
---

* VS2013-VS2019
* 驱动需要 WDK8 以上


使用的第三方库
---

- [curl](https://github.com/curl/curl)
- [mhook](https://github.com/martona/mhook)

其他
---
如果您在使用软件过程中发现Bug，欢迎向我反馈！<br>
如果您有什么软件上的问题、更好的建议或者要求，也可以提issue哦，我会尽量修改程序以满足您的需求。 <br>
您也可以联系我本人 QQ：1501076885 （请备注 **来自JiYuTrainer**）<br>

已测试的版本：
* 极域电子教室：4.0 和 6.0 (这是现在学校使用最广泛的两个版本)
* 系统版本: WinXP SP3,Win7,Win10
