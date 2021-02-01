# op-direct-upgrade
[![Page Views Count](https://badges.toozhao.com/badges/01EXDGR6YMQMV2P89D6WS7EW3Q/green.svg)](https://badges.toozhao.com/stats/01EXDGR6YMQMV2P89D6WS7EW3Q "Get your own page views count badge on badges.toozhao.com")
我是thomaswcy。今天，我来教你如何运用 sysupgrade 命令对软路由进行升级固件的操作。
# 需要的软件
WinScp 下载链接 https://wws.lanzous.com/ivi2ql56mod
# 请将需要使用的固件（img格式，不是压缩包！压缩包请先解压成img）存在本地你记得住的一个文件夹

首先，打开WinScp。登陆教程自己~~百度~~谷歌，懂？

切换到 /tmp 文件夹。在左边选择img镜像所在路径，拖到tmp文件夹里面。

等待复制完成，就点...返回根目录。

在这里，按下快捷键Shift+Ctrl+T，输入以下代码。

注意，<>内的内容请根据img文件名自行修改

```
sysupgrade tmp/<你的文件名>.img
```

点击执行，稍等几秒会出现一个弹窗。在弹窗中，选择确定。

现在，你可以泡一杯咖啡，等大概三分钟，更新就完成了。而且，与以往不同，你的配置在新固件内会被保留，所以基本不需要设置了。但是，我还是建议你检查一下配置，以防万一。

如果出现各种奇奇怪怪的问题，那么我还是劝你重新卡刷，耗子尾汁，不要搞窝里斗。

```
本文作者thomaswcy，在此特别感谢所有对OpenWrt/LEDE有贡献的大佬（Lean，骷髅大佬，东东，...）
```
还有一件事，我特别建议你给骷髅大佬端杯茶

小统计
[![Stargazers over time](https://starchart.cc/thomaswcy/op-direct-upgrade.svg)](https://starchart.cc/thomaswcy/op-direct-upgrade)
