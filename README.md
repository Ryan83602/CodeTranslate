# 代码翻译器

简介:
本项目可以将中文的代码翻译成英文,让编译器能够识别,也可以把英文的源代码翻译成中文,增加可读性

### 支持的语言
JavaScript: 中文<->english<br>
HTML: 中文->english<br>
CPP: 中文->english<br>
### 后续支持
CSS: 中文<->english <br>
CPP: 中文<->english<br>
Java: 中文<->english<br>
HTML: 中文<->english<br>

## 使用方法
1.运行安装脚本
```shell
sh ./Install.sh
```
或者直接
```shell
npm i -g
```
2.翻译
运行安装脚本
```shell
cnjs <cnjs文件> <目标文件> <外接翻译库名>
cnhtml <cnhtm文件> <目标文件>
```
比如说要编译一个有Vue的文件
```shell
cnjs ./index.cnjs ./index.js vue
```
### 开发团队
网络风暴 & Python_Ryan

### 版权声明
需要经过网络风暴 & Python_Ryan审核后方可免费获取版权
