# Dude（大佬）

这是一款手工WEB渗透测试辅助工具，主体程序核心功能为网站浏览，HTTP/S流量数据包截获、修改、重发及基于web的各类型爆破，Poc、Exp验证，程序自带脚本三宝Nmap、Hydra、SQLMap及Awvs14的GUI图形化插件高效率完成日常渗透工作，后续更新工作主要是对主体程序BUG修缮及增加各类型的插件。

## 程序下载 (v1.0.0.3)

**完整绿色版**（不依赖Edge或Edge WebView2 Runtime）  
下载地址：https://github.com/x364e3ab6/Dude/releases/tag/v1.0.0.3  

**实时更新版**（本机需已安装Edge或Edge WebView2 Runtime）  
下载地址：https://codeload.github.com/x364e3ab6/Dude/zip/refs/heads/main  
Edge WebView2： https://developer.microsoft.com/zh-cn/microsoft-edge/webview2/#download-section  

## 更新提示 (v1.0.0.3) 2023.3.25
1. 修改了在安装了Edge或Edge WebView2 Runtime的情况下，可不用携带BrowserRuntime这个超大文件夹；
2. 修改了内置Edge浏览器的一些功能和显示效果；
3. 修改了“数据爆破”功能中同步多线程的问题，极大的提高了爆破速度；
5. 对插件做出一些细节的调整；
4. 修改了一些小Bug。

## 插件下载
Dude Nmap GUI （需本机安装Nmap）  
下载地址：https://github.com/x364e3ab6/Dude/tree/main/Plus/inside/Nmap  

Dude Hydra GUI （无需安装Hydra）  
下载地址：https://github.com/x364e3ab6/Dude/tree/main/Plus/inside/Hydra  

Dude SQLMap GUI （无需安装SQLMap）  
下载地址：https://github.com/x364e3ab6/Dude/tree/main/Plus/inside/SQLMap  

Dude Awvs GUI （需安装Awvs14使用APIKEY进行通讯）  
下载地址：https://github.com/x364e3ab6/Dude/tree/main/Plus/inside/Awvs  

## 运行环境
.Net Framework 4.7.2 （Windows10 1709、Windows Server 1709 版本以上无需额外安装.Net Framework）

## 功能介绍
用户手册实在是懒得写（我错了...请等我的用户手册），粗略介绍一下主要功能和应用范围。

![Dude](https://user-images.githubusercontent.com/73023058/221487446-dcae89e4-fd0a-417c-8771-bbf64d3086e7.jpg)
![Hydra GUI](https://user-images.githubusercontent.com/73023058/221487033-b939846a-43a0-4747-aaa5-ce5973c63546.jpg)
![Nmap GUI](https://user-images.githubusercontent.com/73023058/221487055-d98d4c8d-4e5d-4f45-9177-5c3c05f8f04b.jpg)
![SQLMap GUI](https://user-images.githubusercontent.com/73023058/221487066-dd89f908-a58d-41cd-be9c-60fcd12a63bb.jpg)
![Awvs GUI](https://user-images.githubusercontent.com/73023058/224320478-ddc6fe66-3ce7-4310-8a8a-43400630e9bf.png)

