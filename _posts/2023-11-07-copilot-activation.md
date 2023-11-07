---
layout: post
title: "windowns 11 copilot 激活"
category: notes
---

## 激活copilot
### 一、先让你的 Windows 11 升级到最新的正式版
通过下载 最新 Windows 11 的 ISO 镜像升级并通过 Windows Update 在线更新到最新。要留意重点是要安装好 KB5030310 累积更新补丁，安装后的 Win11 内部版本号为 ···22621.2361···。如果你无法在线更新，可以[手动下载 KB5030310 离线安装包](https://dl.iplaysoft.com/files/5987.html)进行更新。
![1](https://img.iplaysoft.com/wp-content/uploads/2023/win11-copilot/kb5030310.jpg!0x0.webp)
请确保安装好更新补丁后你的 OS 操作系统版本号已是 22621.2361 或更新的版本，再进行下一步，这是必要的基础！版本号可在设置→系统→系统信息里查看，如下图：
![2](https://img.iplaysoft.com/wp-content/uploads/2023/win11-copilot/win11_version_22h2.jpg!0x0.webp)
因为 22621.2361 这个版本号其实很奇妙，虽然系统代号还是 22H2 ，但实际上已经包含了 23H2 的新功能 (包括 Windows Copilot、不合并任务栏等)，只是它们都被微软“隐藏起来”，默认并没有开启而已。

### 二、(可选) 修改区域为美国

由于 Windows Copilot 和一些功能都只在特定国家地区开放，我们最好先将系统区域设置为美国，以方便我们开启它们。与此同时，如果你之前没有安装过 WSA ，其实这时你也可以参考同时[「轻松安装 Android 安卓子系统」](https://www.iplaysoft.com/win11-wsa-install.html)开启更多玩法。

修改 Win11 地区的方法是进入「设置」→「时间和语言」→「区域」→「国家和地区」→选择「美国」即可。这个步骤有些人需要有些人不用，但保险起见，还是建议设置一下避免失败。

### 三、安装 23H2 新功能启用包 (KB5027397 补丁)

**「已经通过镜像安装或升级到“23H2 正式版”的同学无需下载此补丁」**

尽管 23H2 是一个大版本更新，但要从 22H2 最新版 (即 22621.2361) 更新到 23H2，实际上仅需安装一个 180KB 体积的 **「新功能启用包」**（KB5027397 更新补丁），也就是说，微软其只是隐藏掉了新功能，安装补丁后瞬间就能“解开封印”。(下载地址位于本文结尾处)

此升级补丁分为 X64 和 ARM64 两种版本，一般绝大多数普通的 PC 电脑都是 64 位的选 x64，苹果 M 系列的 Mac 或者 Surface 等一些基于 ARM 处理器的设备就选后者。

![3](https://img.iplaysoft.com/wp-content/uploads/2023/win11-copilot/kb5027397.jpg!0x0.webp)

在版本 22621.2361 (KB5030310) 基础上，再安装好此 KB5027397 更新补丁，重启系统之后，系统信息中版本的描述也随着变成 23H2，如下图。

![4](https://img.iplaysoft.com/wp-content/uploads/2023/win11-copilot/win11_version_23h2.jpg!0x0.webp)

此时，我们的正式版 Windows 11 也就能享受到最新的功能了，如无意外的话，我们在任务栏上已经能看到「Windows Copilot」的图标了。

### 三、自行准备好网络条件
但众所周知，无论是 [ChatGPT](https://www.iplaysoft.com/chatgpt.html)、[Bing 必应 AI](https://www.iplaysoft.com/chatgpt.html)，还是你刚开启的 Windows Copilot 这些服务在国内都是无法直接连接的，打开会显示空白或者提示“该服务在你所在的地区不可用”之类的错误。这时你就得自己准备好可用的网络条件才行，这个需要你自己想办法解决。
![5](https://img-dp.iplaysoft.com/dispatch/343cd4159baf37cb2839c6e3580e98c0.gif)

当网络条件允许，尝试过没问题之后，再将区域设置切换回中国即可。这时切换区域，所有的功能包括 Copilot 都是会保留下来的。

### 总结：
使用上面的方法，我们既不需要安装 Windows11 的 Insider Preview 测试版，也不必苦苦等待微软 23H2 全面开放的发布时间。在当前的 Win11 正式版上就能提前享受全新的功能！

由于是官方的升级更新补丁，无需下载第三方工具，而且全程也无需破解或者修改系统内容，因此这个方法没有任何安全风险，对于喜欢尝鲜的同学，可以提前爽爽去了。