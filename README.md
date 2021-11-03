# vue-devtools

![screenshot](./media/screenshot-shadow.png)

[Documentation](https://devtools.vuejs.org/)

### License

[MIT](http://opensource.org/licenses/MIT)

## Sponsors

[💚️ Become a Sponsor](https://github.com/sponsors/Akryum)

[![sponsors logos](https://guillaume-chau.info/sponsors.png)](https://guillaume-chau.info/sponsors)

### 使用教程
[使用教程](https://segmentfault.com/a/1190000014743756)
vue调试工具vue-devtools安装及使用

用户bP7JjP
发布于 2018-05-06
本文主要介绍 vue的调试工具 vue-devtools 的安装和使用。
工欲善其事, 必先利其器, 快快一起来用vue-devtools来调试开发你的vue项目吧。
1.到github下载：git clone https://github.com/vuejs/vue-...

clipboard.png

2.在vue-devtools目录下安装依赖包：

cmd中打开刚刚克隆文件的目录下：（比如我的：F:codevuevue-devtools-master）
clipboard.png

在该目录下安装：npm install
clipboard.png

3.修改manifest.json文件

clipboard.png

将代码中 "persistent":false改成true
clipboard.png

4.安装完成后同在该目录（比如我的：F:codevuevue-devtools-master）下npm run build
clipboard.png

5.扩展Chrome插件

Chrome浏览器 > 更多程序 > 拓展程序
clipboard.png

点击加载已解压程序按钮, 选择 vue-devtools > shells > chrome 放入, 安装成功如下图
clipboard.png

vue-devtools使用
打开vue项目, 打开f12, 选择vue就可以使用了.

vue是数据驱动的, 这样就能看到对应数据了, 方便我们进行调试 ：

clipboard.png
