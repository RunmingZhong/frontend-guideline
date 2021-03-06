# 开发工具

## 编辑器
* [Sublime Text :thumbsup:](https://www.sublimetext.com/3) 跨平台开发神器, 有丰富的扩展支持。 付费，可免费无限期试用.
* [Brackets](http://brackets.io/) Adobe出品的跨平台编辑器, 也有许多扩展
* [Atom](https://atom.io/) Github出品的跨平台编辑器, 仿Sublime Text, 扩展也很丰富
* [notepad++](http://notepad-plus-plus.org/zh/) windows平台, 免费开源, 支持多种语言, 多种文件编码, 支持扩展

### Sublime Text相关网站 :thumbsup:
* [官网](https://www.sublimetext.com/3)
* [Package Control](https://packagecontrol.io/) ST扩展管理器官网
* [Gif Sublime Text常用快捷键](http://blog.jobbole.com/82527/)
* [Sublime Text快捷键及插件推荐](http://www.daqianduan.com/4820.html)

Sublime Text 提供的快捷键相当丰富，若想查看全部的快捷键，从 菜单栏 ➡ Preferences ➡️ Key Bindings - Default 查看所有快捷键的默认配置文件。

### 编辑器扩展
* [Emmet :thumbsup:](http://emmet.io/) 通过易记的缩写形式(支持模糊匹配)来快速生成HTML和CSS, 并配有代码提示, 大大提供输入效率, 减少输错情况.

## API文档查看器 Docset App
集合各种流行编程语言的API文档，方便进行检索查询。下列软件，可根据自身需要，择一即可。

* [Devdocs :thumbsup:](https://devdocs.io/) 在线的API文档合集，并且可将数据缓存至浏览器本地
* [Dash :thumbsup:](https://kapeli.com/dash) Mac平台必备的文档查看器，免费版对文档搜索间隔由8s限制，可内购后解除限制。还可用于管理代码片段，配合Alfred，查询开发文档只在弹指之间。有针对各种流行编辑器对插件，可在编辑器内搜索文档。
* [Velocity :thumbsup:](http://velocity.silverlakesoftware.com/) Dash的windows版，特性一致。也需要付费才能解除搜索的限制。
* [Zeal :thumbsup:](https://zealdocs.org/) windows上的文档查看器，免费开源，体验不如前述App

## 浏览器特性检测
* [Can I Use :thumbsup:](http://caniuse.com/) 浏览器js/css特性兼容性查询
* [Modernizr :thumbsup:](https://modernizr.com/) 检测浏览器特性的js库

## Git 版本控制工具
* [Try git](https://try.github.io/) github 提供的交互教程

## 包管理器, 构建工具(命令行)
* [Nodejs :thumbsup:](http://nodejs.org) 脱离浏览器js运行环境
* [NPM :thumbsup:](http://npmjs.org) nodejs的包管理工具
* [Grunt](http://gruntjs.com) 基于NPM的前端自动化工具
* [Gulp](http://gulpjs.com/) 另一个基于NPM的自动化构建工具

## GUI工具
### prepros (跨平台, 付费， 可免费无限期试用) :thumbsup:
prepro是一款前端工具,内置有web服务器,支持编译各种预编译语言代码(less, sass, coffee等), 自动补全css样式属性的浏览器私有属性, 浏览器实时刷新(编写代码时, 保存代码即刷新), 代码合并及压缩等.

官方网站: <https://prepros.io/>

### codekit (Mac平台, 付费)
codekit和prepos一样, 除了prepos的功能, 还支持管理维护第三方库.

官方网站: <https://incident57.com/codekit/>


### Koala (跨平台, 免费)
koala是一个前端预处理器言图形编译工具，支持Less、Sass、CoffeeScript，帮助web开发者更高效地使用它们进行开发。

官方网站: <http://koala-app.com/index-zh.html>


## 前端代码在线练习及代码片段分享网站
你可以在下述网站在线编写前端代码、查看效果(仅需浏览器，电脑无须安装编辑器及服务器)，并分享给他人(一般均需在网站注册)，也可以在网站上搜索他人分享的有用的代码片段。

支持写 html,css, js(包括引入第三方库):

- <https://jsfiddle.net/>
- <https://codepen.io/>
- <https://jsbin.com/>
- <http://liveweave.com/>
- <https://plnkr.co/>

仅支持 html, css:

- <http://cssdeck.com/>
- <http://dabblet.com/>

## JS函数性能在线测试
当达成一个目的有多种实现方法，你想选择性能最佳的一个时(比如将字符串转换为数字可以用 `+n`, `parseInt(n, 10)`, `Number(n)`), 可在下列网站编写性能测试用例，根据测试结果选择最佳。亦可在下列网站上搜索其他人的性能测试用例。

- <https://jsperf.com/>

## localtunnel
将本机web服务暴露到互联网，得到一个外网可以访问域名(支持https)，方便局域网外的用户访问你的web服务。

官方Repo <https://github.com/localtunnel/localtunnel>

### 安装
```sh
npm install -g localtunnel
```
### 使用

```sh
# 使用 --port 指定本机web服务使用的端口
lt --port 8000
```

执行完命令即可得到一个外网可访问的地址，默认返回 `https` 地址，可手动改为 `http` 来访问。

