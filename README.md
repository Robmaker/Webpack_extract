# Webpack_extract-自动化收集js，自动化加载js

郑重声明：文中所涉及的技术、思路和工具仅供以安全为目的的学习交流使用，任何人不得将其用于非法用途以及盈利等目的，否则后果自行承担。

## 0x01 介绍

作者：[小洲](https://github.com/xz-zone)

团队：[横戈安全团队](img/logo.png)，未来一段时间将陆续开源工具，欢迎关注微信公众号：

![logo](img/logo.png)

定位：协助红队人员快速的信息收集，一键自动加载js。

语言：JS开发

功能：一条龙服务，有发现存在Webpack需要读取的js文件，点击提取映射并且可以获取映射js文件，并且支持一键自动加载js。

支持环境：Chrome。

亮点：本工具已多次在攻防、SRC挖掘场景中出货。 

## 0x02 安装方法

1. 打开Chrome浏览器，访问 `chrome://extensions/`
2. 开启右上角的"开发者模式"
3. 点击"加载已解压的扩展程序"
4. 选择本插件的文件夹
5. 插件安装完成，可在工具栏看到插件图标

## 0x03 效果展示

点击提取映射

![one](img/one.png)

点击一键复制

![two](img/two.png)

点击一键加载

![three](img/three.png)

## 0x04 版本更新

2025-09-01 初始版本提交。

2025-09-16 解决网站兼容性问题。

## 0x05 反馈

Webpack_extract 是一个免费且开源的项目，我们欢迎任何人为其开发和进步贡献力量。

* 在使用过程中出现任何问题，可以通过 issues 来反馈。
* Bug 的修复可以直接提交 Pull Request 到 dev 分支。
* 如果是增加新的功能特性，请先创建一个 issue 并做简单描述以及大致的实现方法，提议被采纳后，就可以创建一个实现新特性的 Pull Request。
* 欢迎对说明文档做出改善，帮助更多的人使用 Webpack_extract。
* 贡献代码请提交 PR 至 dev 分支，master 分支仅用于发布稳定可用版本。

*提醒：和项目相关的问题最好在 issues 中反馈，这样方便其他有类似问题的人可以快速查找解决方法，并且也避免了我们重复回答一些问题。*

## Stargazers over time

[![Stargazers over time](https://starchart.cc/xz-zone/Webpack_extract.svg)](https://starchart.cc/xz-zone/Webpack_extract)


<img align='right' src="https://profile-counter.glitch.me/Webpack_extract/count.svg" width="200">