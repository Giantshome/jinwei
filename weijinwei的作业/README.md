                                             ***我的学习之旅***       

​         *很庆幸能通过程序部一轮面试，并开始我的初步学习之旅。现将部分~~感悟和成果~~（<u>小白</u>）展示如下*：                                                                               

***

​                                                                                                [^我是分割线]                 

> **Git学习之旅**

* 虽然黄学长在Github上分享了Git的具体学习链接，但是文字的东西似乎还是~~有点~~难   [^很蓝的啦]。所以我打开万能的[小破站](https://www.bilibili.com/)，找到了这位大佬[狂神说](https://www.bilibili.com/video/BV1FE411P7B3?from=search&seid=5476894671106223248&spm_id_from=333.337.0.0)。大佬讲解清楚，从Git[^分布式代码管理系统]的安装到原理使用均有涉及。我记得自己第一次使用Git时连用户名和邮箱也不会设置，因为全部是英文，我只能照猫画虎打上

  ```
  $ git config --global user.name "Your Name"
  $ git config --global user.email "email@example.com"
  ```
  
  当然直接提示**command not found**！
  
  <img src="D:\用户\Jinwei\Desktop\QQ图片20210921140753.png" style="zoom:20;" />

  

  后来发现是复制时多了$，导致报错！设置好后用`Git config -l`提示正常

  * 在设置好用户后，一切变得容易起来，首先用`Git init`把我的学习目录变成Git可以管理的仓库，资源管理器里出现了隐藏的`.Git`文件夹，我再新建了一个名为123的文本文档，然后`Git add` . 从**workspace**添加到**stage**,然后用`Git commit -l`，放到**repository** 
  
  * 之后我又试了试从远程服务器**Git clone** 到本地，提示克隆成功。
  
    <img src="C:\Users\动物世界\AppData\Roaming\Typora\typora-user-images\image-20210921150703319.png" alt="image-20210921150703319" style="zoom:50%;" />
  
* <img src="C:\Users\动物世界\AppData\Roaming\Typora\typora-user-images\image-20210921150813754.png" alt="image-20210921150813754" style="zoom:30%;" />



------

------



> **Markdown学习记录** 

- 个人觉得Markdown要比Git稍微简单[^主要是因为有交互界面，不像Git bash一样一切操作靠代码]，基本上全部是***typora***的使用，这个软件写写笔记确实使用，当然得记住一些符号搭配，我所学习的如下:

  | 符号搭配            | 效果展示                                                     |
  | ------------------- | ------------------------------------------------------------ |
  | <                   | <img src="C:\Users\动物世界\AppData\Roaming\Typora\typora-user-images\image-20210921153316320.png" alt="image-20210921153316320" style="zoom:%;" /> |
  | *   *               | *斜体*                                                       |
  | **  **              | **粗体**                                                     |
  | ***  ***            | ***粗斜体***                                                 |
  | *                   | ![image-20210921153754481](C:\Users\动物世界\AppData\Roaming\Typora\typora-user-images\image-20210921153754481.png) |
  | >                   | ![image-20210921153850475](C:\Users\动物世界\AppData\Roaming\Typora\typora-user-images\image-20210921153850475.png) |
  | >>>                 | ![image-20210921153929116](C:\Users\动物世界\AppData\Roaming\Typora\typora-user-images\image-20210921153929116.png) |
  | >>                  | ![image-20210921153942733](C:\Users\动物世界\AppData\Roaming\Typora\typora-user-images\image-20210921153942733.png) |
  | [链接]+ (地址)      | [你好帅](www.baidu.com)                                      |
  | 图片                | 直接右键                                                     |
  | \|  第一 \|第二  \| | 比如这个表格就是效果展示                                     |
  | =======             | 标记一级标题                                                 |
  | ---------           | 标记二级标题                                                 |
  |                     |                                                              |
  |                     |                                                              |

  > **如果进入程序部想学的内容**

1. 学习c++，Java，HTML等主流编程语言，编写自己的程序
2. 了解windows，Android等操作系统结构和组成
3. 熟练使用注册表，组策略等

[^很蓝的啦]: 赢不下来吧，很蓝的啦

[^分布式代码管理系统]: 百度一下，你就知道！
[^我是分割线]: 就单纯的分割线