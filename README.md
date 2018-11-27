# Fawanhu 矢量图标库

## 关于Fawanhu矢量图标库

矢量图标库相当于一款字体库，字库中的ASCII和定义的每个图标会有一个对应关系，好比我们原来的字体库中的字母“A”被“房子”图标替代了，在css伪类中的content属性写入该图标的编码，这样就能在UI层面表现出该图标样式。

而矢量图标库的具有体积小、请求次数少、自适应等优秀特性，在大型产品平台中其优势远远大于图片化图标

## 使用Fawanhu

在同步演示页上查看：http://192.168.0.223:8089/fff76ca0/0/frontend/FaWanhu/demo.html （[右点我新窗口打开](http://192.168.0.223:8089/fff76ca0/0/frontend/FaWanhu/demo.html)）
和UI设计师确定使用哪个图标之后，在上述演示页中查找到该图标，获取到图标的代码标识，即可完成使用

**示例**，使用搜索图标：

```html
<i class="fa fa-search"></i>
```

如果希望在低版本游览器（IE7）中表现该图标，需要使用下述字符串

```html
<i class="fa fa-search">&#xf092;</i>
```

**注意仅在IE7中，回到[演示页](http://192.168.0.223:8089/fff76ca0/0/frontend/FaWanhu/demo.html)中查看到`&#xf092;`的`&`是`!`，实际使用过程中务必改为`&`**。

## 微信版OA

微信版OA V2、V3版暂未移植Fawanhu图标库，使用的仍然是第三方图标库：[Font-Awesome](http://fortawesome.github.io/Font-Awesome/icons/)  使用原理完全相册，和Fawanhu的不同之处在于图标对应编码不相同