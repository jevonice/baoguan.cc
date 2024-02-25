### 进口报关

默认情况下，当前页面上的超链接被识别，内容保存在`localStorage`. 您还可以指定文件的路径。



此插件在执行全文搜索时会忽略变音符号（例如，“cafe”也将匹配“cafe”）。像 IE11 这样的旧版浏览器需要以下[String.normalize() polyfill](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/normalize)来忽略变音符号：



### 表情符号

默认支持解析表情符号。例如`:100:`将解析为但这并不精确，因为没有匹配的非表情符号字符串。如果您需要正确解析表情符号字符串，则需要安装此插件。



### 外部脚本

如果页面上的脚本是外部脚本（通过`src`属性导入 js 文件），则需要此插件才能使其工作。



### 缩放图像

中的图像缩放。基于[中变焦](https://github.com/francoischalifour/medium-zoom)。



