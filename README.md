# DragonReader - 青龙小说下载阅读器

`青龙小说` 是一个基于其他搜索引擎构建的小说预览工具，目的是让阅读更简单、优雅，让每位读者都有舒适的阅读体验

> 注意：若将本项目发行，请声明来源，本项目纯属共享学习之用，不得用于商业！

## 特色
* 无需写任何特定源解析规则（含用户及开发者），仅依赖bing/sogou/360三个搜索引擎
* 丰富的资源，涵盖网络小说、女频小说、经典小说等
* 自动精校，去除大部分文字级别的小广告（如xxx手打网推荐）
* 跨平台，iOS/MacOS/Android/Windows/Linux（感谢Cordova和Electron）
* 纯客户端运行，无需部署任何服务器

## 技术
使用TypeScript + Angular + Electron / Cordova
更详细的文档待编写

## 进度

- [X] 爬虫核心（搜索、下载、精校）
- [ ] 其他大部分功能 :)

## 如何运行
> 当前仅有少部分功能可以运行

初次配置
1. 确保NodeJS已安装，版本10+
2. 确保Electron已安装，安装指令 `npm i -g electron`
3. 确保Angular已安装，安装指令 `npm i -g @angular/cli`
4. 在项目目录下，安装依赖库`npm i`

每次运行
1. 在项目目录下，运行`ng serve`
2. 在项目目录下，另启一个命令行，运行`electron index`