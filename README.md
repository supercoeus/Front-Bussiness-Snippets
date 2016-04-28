# 前端业务层代码片段
## 代码片段有利于解决以下问题

* 使用了相同组件的页面，结构是相仿的，相仿的代码往往会在之前的页面代码基础上修改，
  第一，需要对变量统一修改（查找，修改），第二，要将之前没用的代码给删除，最后很
  可能会出现因为改错而产生莫名的bug。此时将组件使用的最少化代码作为代码片段，开
  发时，只需敲打几个字母就能输出，通过Tab来控制需要重新命名的变量，或增删配置项
  就可以了。

* 就是短小的代码，如获取前端配置，调用基类同名方法，开启菊花，关闭菊花...这些代
  码是可以抽取出来作为片段，达到快速编写代码，而且不容易写错。


## js 代码块集合 文件夹，包含若干sublime-snippet文件

* codeblock  简短代码块，通常在两行代码以内
* datacenter 发起异步请求方法，包含GET/POST/ABORT
* page       页面级别代码
* view       视图级别代码
* weixin     微信JS API代码（只收录了添加会员卡到卡包接口）

## html 代码块 sublime-snippet文件

* layout     单一区域HTML布局
* layouthb   包含2个区域（头部，身体）的HTML布局
* layouthbf  包含3个区域（头部，身体，底部）的HTML布局
* list       列表HTML布局

## css 代码块 sublime-snippet文件

* layout     单一区域CSS
* layouthb   包含2个区域（头部，身体）的CSS
* layouthbf  包含3个区域（头部，身体，底部）的CSS
* list       列表CSS

## License

MIT
