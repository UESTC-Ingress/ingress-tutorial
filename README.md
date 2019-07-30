# Ingress 中文游戏指南

**正在写作中。**
本书是由电子科大Ingress社团Fork的版本。

## 在线阅读本书

https://tutorial.nia.ac.cn

## 自行编译

依赖项：
 * [node.js](https://nodejs.org/)
 * [gitbook-cli](https://github.com/GitbookIO/gitbook-cli)

  ```shell
  $ npm install gitbook-cli -g
  ```
 * [gitbook-plugin-fancybox](http://plugins.gitbook.com/plugin/fancybox)

  ```shell
  $ npm install --save gitbook-plugin-fancybox
  ```
 * [gitbook-plugin-addcssjs](http://plugins.gitbook.com/plugin/addcssjs)

  ```shell
  $ npm install --save gitbook-plugin-addcssjs
  ```

然后 clone 本书
```shell
$ git clone --depth 1 https://github.com/UESTC-Ingress/ingress-tutorial.git
```

接下来你可以选择其中一种方法来查看本书的内容：

* 构建静态 HTML 页面

  ```shell
  $ gitbook build
  ```
  完成后页面将会存放在 `_book` 目录中。

* 直接在浏览器中观看

  ```shell
  $ gitbook serve
  ```

## 参与项目

合作请联系： tutorial[#]nia.ac.cn

## 版权

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">Ingress 中文游戏指南</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://www.gitbook.com/book/hz-ingress/ingress-tutorial/" property="cc:attributionName" rel="cc:attributionURL">Hangzhou Ingress Group</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/hz-ingress/ingress-tutorial" rel="dct:source">hz-ingress/ingress-tutorial</a>.
