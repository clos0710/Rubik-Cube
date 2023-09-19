<p align="center"><img width="400px" src="https://github.com/clos0710/Rubik-Cube/blob/master/img/Cube.png" /></p>

## 📖 目录结构

[📰 魔方故事](https://github.com/clos0710/Rubik-Cube#%EF%B8%8F-%E9%AD%94%E6%96%B9%E6%95%85%E4%BA%8B) | [✏️ 心路历程](https://github.com/clos0710/Rubik-Cube#%EF%B8%8F-%E5%BF%83%E8%B7%AF%E5%8E%86%E7%A8%8B) | [🤨 实物还原](https://github.com/clos0710/Rubik-Cube#-%E5%AE%9E%E7%89%A9%E8%BF%98%E5%8E%9F)

## 📰 魔方故事

- 魔方的由来

> 鲁比克·艾尔诺是匈牙利的建筑学和雕塑学教授。为了帮助学生们认识空间立方体的组成和结构，动手做出了魔方的雏形，灵感来自多瑙河中的沙砾。
>
> 1974年，鲁比克教授发明了第一个魔方，当时称作Magic Cube，并在1975年获得匈牙利专利。
>
> 1979年，Ideal Toys公司将魔方带至全世界，并于1980年在伦敦、巴黎和美国的国际玩具博览会亮相。展出之后，Ideal Toys公司将魔方的名称改为Rubik's Cube。
>
> —— 百度百科

- 魔方的外观

> 魔方六个面贴纸通常由红、黄、蓝、绿、白、橙六种颜色组成，基本上是前红、后橙、上黄、下白、左蓝、右绿。
>
> 魔方并不只有一种配色方案，现今所流行的并非最初的版本。现今的配色方案是将一对相似色系的颜色安排在相对两边。
>
> 魔方由一个连接着6个中心块的中心轴以及8个角块，12个棱块构成，当它们连接在一起的时候会形成一个整体，并且任何一面都可水平转动而不影响到其他方块。
>
> 官方版本魔方边长为57毫米，当前主流竞速三阶尺寸多为55-57毫米。
>
> —— 百度百科

[🚀 回到目录](https://github.com/clos0710/Rubik-Cube#-%E7%9B%AE%E5%BD%95)

## ✏️ 心路历程

有一天下班回家，儿子蹦蹦跳跳地和我说，爸爸我有个新玩具，你看。

原来是个崭新的魔方，一下让我想起来，十几年前自己也买过一个，还挺贵，是个比赛用魔方。

为了防止魔方被弄脏，我还专门找了一个布口袋装它。

翻箱倒柜找出来当年的魔方。颜色已经变暗了很多，拧起来也不那么顺畅了。

还记得魔方拿到手的时候，我到处找魔方还原的教程。**那时候不像现在有视频教学，全是图片和字母公式，复杂又难记，一步拧错挫败感很强。**

学了几天实在没有耐心，于是魔方成了书桌上的摆件，所幸的是搬家时没有丢掉。

如今小家伙也开始拧魔方了，一下勾起了我的回忆。这次说什么也要学会，未来可以教儿子怎么还原。

于是，我给自己定了三个目标：**一是将实物魔方还原的步骤总结下来形成笔记、二是将还原公式变的容易记忆、三是用Java实现一个数字版魔方。**

[🚀 回到目录](https://github.com/clos0710/Rubik-Cube#-%E7%9B%AE%E5%BD%95)

## 🤨 实物还原

> 为之则难者亦易矣，不为则易者亦难矣。
>
> —— 《为学一首示子侄》 清· 彭端淑

经过两周的视频学习，终于可以使用**层先法**还原魔方。家人说我着了魔似的，一有空就在拧。其实是公式不太熟，多拧几次记得牢。

在介绍**层先法**前，先对三阶魔方做一个介绍和约定：

1. 魔方分层

    **三层：底层、二层、顶层。分层法的基本思路是逐层还原。**

    <p align="center"><img width="300px" src="https://github.com/clos0710/Rubik-Cube/blob/master/img/CubeSolve1.png" /></p>

    **为了形象展示，我借助了github上的优秀项目[魔方栈](https://github.com/huazhechen/cuber)（[在线体验](https://huazhechen.gitee.io/cuber/)）截图展示。**

2. 魔方分块

    **26块：6个中心块，12个棱块，8个角块。中心块 —— 一种颜色，棱块 —— 两种颜色，角块 —— 三种颜色。**

    <p align="center"><img width="300px" src="https://github.com/clos0710/Rubik-Cube/blob/master/img/CubeSolve2.png" /></p>

3. 魔方旋转

    **左右手各握持一边，一面朝内。**
    
    <p align="center"><img width="300px" src="https://github.com/clos0710/Rubik-Cube/blob/master/img/CubeSolve3.png" /></p>
    
    **下面的内容非常重要，是魔方还原的旋转手法，请牢记！**
    
    <p align="center"><img width="300px" src="https://github.com/clos0710/Rubik-Cube/blob/master/img/CubeSolve4.png" /></p>
    
    