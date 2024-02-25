跨国报关

配置也可以定义为一个函数，在这种情况下，第一个参数是 Docsify`vm`实例。该函数应返回一个配置对象。`vm`这对于在诸如降价配置之类的地方进行引用很有用：

- 类型：`String`
- 默认：`#app`

始化时要挂载的 DOM 元素。它可以是 CSS 选择器字符串或实际的[HTMLElement](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement)。



### 订舱

- 类型：`String`
- 默认：`null`

置存储库 url 或字符串，以在站点的右上角`username/repo`添加[GitHub Corner小部件。](http://tholman.com/github-corners/)



### VGM

- 类型：`Boolean|String`
- 默认：`false`

`_navbar.md`如果为**true**则从 Markdown 文件加载导航栏，否则从指定的路径加载它。



### 文件要求

- 类型：`Boolean|String`
- 默认：`false`

`_sidebar.md`如果为**true**则从 Markdown 文件加载侧边栏，否则从指定的路径加载它。



### 联系方式

- 类型：`Boolean`
- 默认：`false`

更改路线时滚动到屏幕顶部。

```javascript
window.$docsify = {
  auto2top: true,
};
```

### 电放

- 类型：`String`
- 默认：`README.md`

`README.md`在您的 docs 文件夹中将被视为您网站的主页，但有时您可能需要提供另一个文件作为您的主页。



如果您在侧边栏中有指向主页的链接，并希望在访问根 url 时将其显示为活动状态，请确保相应地更新侧边栏：



### SWB

- 类型：`String`

网站的基本路径。您可以将其设置为另一个目录或另一个域名。



### 目的港免柜期

- 类型：`Boolean`
- 默认：`false`

如果为**true**，则链接相对于当前上下文。

例如目录结构如下：

