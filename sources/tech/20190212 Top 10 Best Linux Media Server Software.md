[#]: collector: (lujun9972)
[#]: translator: (kodark)
[#]: reviewer: ( )
[#]: publisher: ( )
[#]: url: ( )
[#]: subject: (Top 10 Best Linux Media Server Software)
[#]: via: (https://itsfoss.com/best-linux-media-server)
[#]: author: (Ankush Das https://itsfoss.com/author/ankush/)

10个最好的Linux媒体服务器软件
======
是否有人和你说Linux是程序员的专属？这个说法过于绝对！因为Linux也为数字艺术家、作家和音乐家提供了很多很好的工具。
我们以前也介绍过这类应用，但今天的话题可能会有些许不同。我们主要谈论它引人之处，而不是使用方法。
你可曾听说过媒体服务器？这些软件(或者小工具)可以让你直观的浏览你本地或者云端的媒体(像音乐、视频之类的)，也可以用它来发送内容到你网络上的其他设备上。就像你的个人Netflix一样。
本文将介绍一些Linux上优秀的媒体软件，你可以根据个人需求来选择将它用作媒体播放器还是媒体服务器软件。
一些应用还可以和谷歌的Chromecast、亚马逊的Firestick协同使用。
### Best Media Server Software for Linux
###Linux上最优秀的媒体服务器软件

![Best Media Server Software for Linux][3]

软件排名不分先后。
我以前发布了关于Ubuntu和Debian的安装方法。但是不可能列出在所有Linux发行版的安装步骤，为此感到抱歉。
所介绍的某些软件是不开源的，等下我会着重强调。
### 1\. Kodi

![Kodi Media Server][4]

Kod是最流行的媒体服务器软件和播放器之一。最近，Kodi 18.0推出了一系列改进，包括对数字版权管理(DRM)解密、游戏仿真器、rom、语音控制等的支持。
它是完全免费的开源软件。有一个活跃的社区可以讨论和为它提供支持。Kodi的用户界面很漂亮。它的早期版本，我没有机会使用——但是看到一个Linux应用程序有这么好的UI，我很惊讶。
它有有强大的回放支持-你可以添加任何它所支持的第三方媒体服务内容或手动添加视频文件观看。
####怎样安装Kodi
在终端中输入以下命令，通过其[官方PPA][5]安装Kodi的最新版本。
```
sudo apt-get install software-properties-common
sudo add-apt-repository ppa:team-xbmc/ppa
sudo apt-get update
sudo apt-get install kodi
```

要了解更多关于安装开发构建或升级Kodi的信息，请参考[正式安装指南]
### 2\. Plex

![Plex Media Server][7]

Plex是另一个受大众喜爱的媒体播放器，也可以用作媒体服务器软件来使用。对用户来说，它是Kodi的很好的替代品，主要用它来创建一个离线网络，同步和跨设备观看他们的内容。
与Kodi不同，Plex并不是完全开源的。它提供了免费帐户来使用它。它也还提供了功能多而强大的付费服务，并对媒体有更多的修改，同时也能获得关于如何使用Plex的详细信息。
如果你是一个音乐发烧友，你会喜欢Plex与[TIDAL][8]音乐流媒体服务的整合。你还可以通过将其添加到调谐器来直播电视。
#### 怎样安装Plex
你可以直接从官网上下载.deb软件包安装。
### 3\. Jellyfin

![Emby media server][10]

这是一个很有特色的开源媒体服务器软件。Jellyfin实际上是Emby media server的一个分支。
它是也许是最好的免费产品之一，但目前还不支持多平台。
你可以在浏览器上运行它，也可以通过Chromecast使用。但是，如果你想要在Android应用设备上使用或者你想让它支持其它设备，你就得等一等。
####怎样安装Jellyfin
Jellyfin提供了[详细文档]，介绍了怎样用Linux、Docker等的可用二进制包/镜像来安装他。
你也可以通过基于debian的发行版的命令行从存储库中很容易的安装它。查看他们的[安装指南]以获得更多信息。

### 4\. LibreELEC

![libreELEC][14]

LibreELEC是一个很有意思的媒体服务器软件，它基于Kodiv18.0.他们最近发布了一个新版本(9.0.0)­——对核心操作系统支持、硬件兼容性和用户体验进行了彻底的革新。
当然了，基于Kodi也有DRM的支持。另外，你可以使用Linux通用版、Raspberry版、或者WETek设备特殊定制版。

你可以从官网上下载，也可以查看LibreELEC安装指南。
### 5\. OpenFLIXR Media Server

![OpenFLIXR Media Server][17]

你是否在寻找一款类似Plex这样优秀的媒体服务，还想与虚拟机兼容的应用？下面将为你介绍！
OpenFLIXR是一款自动媒体服务器软件，它与Plex集成，提供所有功能，包括用torrent自动下载电视节目和电影。
你也可以安装一个自动家庭影院。如果你不想在实体机上运行它——没关系，它支持主流的虚拟机(VMware、VirtualBox、Hyper-V)。更棒的是他是基于Ubuntu服务器的开源方案。
####怎样安装OpenFLIXR
最简单有效的方法就是把它安装在VirtualBox中。安装完成后，从官网下载导入即可。
### 6\. MediaPortal

![MediaPortal][19]

MediaPortal是一款开源而且简洁的流媒体服务软件，他有个性化的用户界面，但我不希望Kodi也这么做。
你可以在本地网络上播放dvd、流媒体视频，还可以听音乐。它没有提供一些花哨的功能，但有你最需要的功能。
你可以安装稳定版或测试版(功能新且不稳定)。
####怎样安装MediaPotal
根据你想安装的功能(仅设置电视服务器或完整的服务器设置)，请参照官方[详细文档]安装。
### 7\. Gerbera

![Gerbera Media Center][21]

媒体服务器可以在本地网络中实现简单的数据传输。它支持转码，将媒体转码为你的设备支持的格式
如果你使用媒体服务已经很长时间了，那么你可以把它当作MediaTomb的改进版。尽管它在Linux中不是主流版本，但当其它媒体服务不可用或对于喜欢简洁的媒体服务器的人来说他是一个不错的选择。
####怎样安装Gerbera
在终端里运行以下几条命令安装
```
sudo apt install gerbera
```

其他版本Linux可以参考[官方文档]
###8\.OSMC(开源媒体中心)
![OSMC Open SourceMedia Center][23]

这是一个外观的媒优美的媒体服务器软件，最初基于Kodi媒体中心。我对它的用户界面印象深刻。它简单而强悍，是一套免费的开源解决方案。简而言之，你想要的它基本都有。
你可以购买OSMC的旗舰机，它可以轻松播放几乎所有4K视频。此外，它兼容树莓派和第一代苹果电脑。
#### 怎样安装OSMC
你可以选择兼容你设备和操作系统的版本，并从官网上下载安装程序来安装该应用。
### 9\. Universal Media Server

![][25]

简单的介绍一下UniversalMedia Server，他没有花里胡哨的功能，只可以转码/在线欣赏音视频。
它支持Xbox 360、PS3，以及其它支持[DLNA]的设备。
#### 怎样安装Universal Media Center
你可以在[FoeeHub]上找到安装包，建议从官网下载安装。
### 10\. Red5 Media Server

![Red5 Media Server][29]Image Credit: [Red5 Server][30]

它是一个免费且开源的企业级定制版的媒体服务器。可以用来直播——无论是娱乐还是视频会议。
他们还为手机端提供付费服务和高扩展性。

建议按照GitHub上的[安装指南]来安装。
差不多就介绍这些吧
这里所介绍的每一个软件都有自己的特色和优点——选择一个适合自己的即可。
你还有其它推荐的吗？欢迎在下方评论！

--------------------------------------------------------------------------------

via: https://itsfoss.com/best-linux-media-server

作者：[Ankush Das][a]
选题：[lujun9972][b]
译者：[kodark](https://github.com/kodark)
校对：[校对者ID](https://github.com/校对者ID)

本文由 [LCTT](https://github.com/LCTT/TranslateProject) 原创编译，[Linux中国](https://linux.cn/) 荣誉推出

[a]: https://itsfoss.com/author/ankush/
[b]: https://github.com/lujun9972
[1]: https://itsfoss.com/best-linux-graphic-design-software/
[2]: https://itsfoss.com/open-source-tools-writers/
[3]: https://i0.wp.com/itsfoss.com/wp-content/uploads/2019/02/best-media-server-linux.png?resize=800%2C450&ssl=1
[4]: https://i0.wp.com/itsfoss.com/wp-content/uploads/2019/02/kodi-18-media-server.jpg?fit=800%2C450&ssl=1
[5]: https://itsfoss.com/ppa-guide/
[6]: https://kodi.wiki/view/HOW-TO:Install_Kodi_for_Linux
[7]: https://i1.wp.com/itsfoss.com/wp-content/uploads/2019/02/plex.jpg?fit=800%2C368&ssl=1
[8]: https://tidal.com/
[9]: https://itsfoss.com/gdebi-default-ubuntu-software-center/
[10]: https://i1.wp.com/itsfoss.com/wp-content/uploads/2019/02/emby-server.jpg?fit=800%2C373&ssl=1
[11]: https://jellyfin.github.io/
[12]: https://jellyfin.readthedocs.io/en/latest/
[13]: https://jellyfin.readthedocs.io/en/latest/administrator-docs/installing/
[14]: https://i2.wp.com/itsfoss.com/wp-content/uploads/2019/02/libreelec.jpg?resize=800%2C600&ssl=1
[15]: https://libreelec.tv/downloads_new/
[16]: https://libreelec.wiki/libreelec_usb-sd_creator
[17]: https://i1.wp.com/itsfoss.com/wp-content/uploads/2019/02/openflixr-media-server.jpg?fit=800%2C449&ssl=1
[18]: http://www.openflixr.com/#Download
[19]: https://i2.wp.com/itsfoss.com/wp-content/uploads/2019/02/mediaportal.jpg?ssl=1
[20]: https://www.team-mediaportal.com/wiki/display/MediaPortal1/Quick+Setup
[21]: https://i1.wp.com/itsfoss.com/wp-content/uploads/2019/02/gerbera-server-softwarei.jpg?fit=800%2C583&ssl=1
[22]: http://docs.gerbera.io/en/latest/install.html
[23]: https://i2.wp.com/itsfoss.com/wp-content/uploads/2019/02/osmc-server.jpg?fit=800%2C450&ssl=1
[24]: https://osmc.tv/download/
[25]: https://i0.wp.com/itsfoss.com/wp-content/uploads/2019/02/universal-media-server.jpg?ssl=1
[26]: https://en.wikipedia.org/wiki/Digital_Living_Network_Alliance
[27]: https://www.fosshub.com/Universal-Media-Server.html?dwl=UMS-7.8.0.tgz
[28]: https://www.universalmediaserver.com/forum/viewtopic.php?t=10275
[29]: https://i1.wp.com/itsfoss.com/wp-content/uploads/2019/02/red5.jpg?resize=800%2C364&ssl=1
[30]: https://www.red5server.com/
[31]: https://github.com/Red5/red5-server/wiki/Installation-on-Linux
[32]: https://i0.wp.com/itsfoss.com/wp-content/uploads/2019/02/best-media-server-linux.png?fit=800%2C450&ssl=1
