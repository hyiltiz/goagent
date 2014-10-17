goagent 3.2.0 正式版下载 [http://git.io/goa](https://nodeload.github.com/goagent/goagent/legacy.zip/3.0)

## 简易教程

- 部署

  1. 申请 [Google Appengine](https://appengine.google.com) 并创建 appid。
  1. 下载 goagent 后修改 local\proxy.ini 中的 [gae] 下的 appid = 你的appid(多appid请用|隔开)
  1. 运行 uploader.bat 或 uploader.py 开始上传, 成功后即可使用了。

- 使用

  * Windows 用户推荐使用 goagent.exe 托盘图标设置 IE 代理(对其它浏览器也有效)。
  * Chrome/Opera 请安装 [SwitchySharp](https://chrome.google.com/webstore/detail/dpplabbmogkhghncfbfdeeokoefdjegm) 插件(拖放  SwitchySharp.crx 到扩展设置)，然后导入 SwitchyOptions.bak
  * Firefox 请安装 [FoxyProxy](https://addons.mozilla.org/zh-cn/firefox/addon/foxyproxy-standard/) ，Firefox需要导入证书，方法请见 FAQ
  * 出现连接不上的情况可以尝试使用 [GoGo Tester](https://github.com/azzvx/gogotester/raw/2.3/GoGo%20Tester/bin/Release/GoGo%20Tester.exe) 测速。

## 讨论区
* https://code.google.com/p/goagent/issues/list

## 文档
* 图文教程 https://goagent.github.io/?/wiki/InstallGuide.md
* 常见问题 https://goagent.github.io/?/wiki/FAQ.md
* 配置介绍 https://goagent.github.io/?/wiki/ConfigIntroduce.md
* 五毛观止 https://goagent.github.io/?/wiki/SpamList.md
* 更新历史 https://goagent.github.io/?/wiki/History.md

## 代码
 * proxy.py https://github.com/goagent/goagent/tree/3.0
 * python27.exe https://github.com/goagent/pybuild
 * goagent.exe https://github.com/goagent/taskbar
