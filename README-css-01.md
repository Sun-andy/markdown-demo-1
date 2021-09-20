# css基础概念

## 一、css是谁发明的？

李爵士的挪威同事赖先生首先提出css

## 二、css的版本

css2.1 2004-2011年 使用最广泛的版本
css3 1999年开始起草 现代版本，分模块

## 三、怎么知道浏览器支持哪些特性？

使用caniuse.com

## 四、如何调试css？

用border调试法
加border 边框，border出现了，说明前面代码没问题，border没出现，说明前面有代码错误。

## 五、在哪查资料？

* Google搜索关键词时加mdn
* css tricks(英文)
* 张鑫旭的博客

## 六、在哪搜练习素材？

* PSD
freepik 搜索PSDweb
中文psd网站较少，可以搜365PSD里的UI套件还行

* 效果图
* dribbble.com顶级设计师社区
* 可以用肉眼来模仿它（每个模仿两个即可）

## 七、标准制定者是谁？

W3C 可以看css2.1标准的中文版

## 八、文档流

* 流动方向
inline 元素从左到右，到达最右边才会换行
block 元素从上到下，每一个都另起一行
Inline-block 也是从左到右

* 宽度
inline 宽度为内部inline 元素的和，不能用width指定
block 默认自动计算宽度，可用width 指定
inline-block 结合前两者特点，可用width

* 高度
inline 高度有line-height 间接确定，跟height无关
block 高度由内部文档流决定，可以设height
inline-block 跟block 类似，可以设置height

## 九、overflow 溢出

### 当内容大于容器
用overflow设置
* auto灵活设置
* scroll以滚动条显示
* hidden 直接隐藏溢出部分
* visible 直接显示溢出部分

## 十、脱离文档流

* float
* position：absolute/fixed

## 十一、两种盒模型

* 分别是
content-box 内容盒-内容就是盒子的边界
border-box 边框盒-边框就是盒子的边界

* 公式
content-box 的width=内容宽度
border-box 的width=内容宽度+padding+border

## 十二、margin合并

* 哪些情况会和并？
父子margin合并
兄弟margin合并

* 如何阻止合并？
父子合并用padding/border挡住
父子合并用overflow：hidden 挡住
父子合并用display：flex 挡住
兄弟合并是符合预期的
兄弟合并可以用Inline-block消除




