# 常用细节

## 设置代码检查等级

![&#x914D;&#x7F6E; &#x4EE3;&#x7801;&#x68C0;&#x67E5;&#x7B49;&#x7EA7;](../../.gitbook/assets/xxxiv-often-use-a-1.jpg)

> * 上图中会有常见的几种波浪线， 红色的波浪线为错误。如果含有则此程序含有语法上的错误。黄色为拼写不规范。灰色为未用到的变量。 为保证代码优雅，建议不要出现上图中的任何波浪线。

![&#x914D;&#x7F6E; &#x4EE3;&#x7801;&#x68C0;&#x67E5;&#x7B49;&#x7EA7;](../../.gitbook/assets/xxxiv-often-use-a-7.jpg)

> * 如上所示，默认是开启单词拼写检查的，有些人可能有强迫症不喜欢看到单词下面有波浪线，就可以去掉该勾选。但是我个人建议这个还是不要关闭，因为拼写检查是一个很好的功能，当大家的命名都是标准话的时候，这可以在不时方便地帮我们找到代码因为拼写错误引起的 Bug。

![&#x914D;&#x7F6E; &#x4EE3;&#x7801;&#x68C0;&#x67E5;&#x7B49;&#x7EA7;](../../.gitbook/assets/xxxiv-often-use-a-2.jpg)

> * 上图中点击头像图标，会出现检测等级。从上而下意思为严格检查，一般检查和不检测
> * Power save mode 叫做 省电模式 的状态，开启这种模式之后会关掉代码检查和代码提示等功能。所以一般认为这是一种 阅读模式，如果你在开发过程中遇到突然代码文件不能进行检查和提示可以来看看这里是否有开启该功能。
> * Configure inspections

## 代码提示

![&#x914D;&#x7F6E; &#x4EE3;&#x7801;&#x63D0;&#x793A;](../../.gitbook/assets/xxxiv-often-use-a-3.jpg)

> * 代码提示和补充功能有一个特性：区分大小写。如上图所示，默认就是 `First letter` 区分大小写的。
> * 区分大小写的情况是这样的：比如我们在代码文件中输入 `ECHO` 是不会帮我们提示或是代码补充的，但是如果我们输入 `echo` 就可以进行代码提示和补充。
> * 如果想不区分大小写的话，改为 `None` 选项即可。

## 自动导入

![&#x914D;&#x7F6E; &#x81EA;&#x52A8;&#x5BFC;&#x5165;](../../.gitbook/assets/xxxiv-often-use-a-4.jpg)

> * php的自动导入不是很多，如图所示，当需要时会自动导入`namespace`

## 代码折叠

![&#x914D;&#x7F6E; &#x4EE3;&#x7801;&#x6298;&#x53E0;](../../.gitbook/assets/xxxiv-often-use-a-5.jpg)

> * 如上图标注所示，我们可以对指定代码类型进行默认折叠或是展开的设置，勾选上的表示该类型的代码在文件被打开的时候默认是被折叠的，去掉勾选则反之。

## 分割代码

![&#x914D;&#x7F6E; &#x5206;&#x5272;&#x4EE3;&#x7801;](../../.gitbook/assets/xxxiv-often-use-a-6.jpg)

> * 一般在对大文件进行修改的时候，有些修改内容在文件上面，有些内容在文件下面，如果来回操作可能效率会很低，用此方法就可以好很多。

## 常用的快捷键

> * 撤销 ： `command + Z` 
> * 反撤销： `command + shift + Z`  
> * 复制上一行 :`command + D`  
> * 剪切当前行: `command + X`  
> * 上下行交换: `alt + shift + ↑↓`  
> * 当前选中行注释: `command + /`  
> * 多行注释： `command + shift + /`  
> * 搜索当前文件 ：`command + F` 
> * 替换当前文件：`command + R`  
> * 搜索项目：`command + shift + F` 
> * 替换项目：`command + shift + R` 
> * 选中多个当前的单词 ：`ctrl + G` 
> * 快速查找方法： `command + alt + O` 
> * 快速查找文件：`command + shift + O`

## PHPDOC 自动生成

![&#x914D;&#x7F6E; PHPDOC &#x81EA;&#x52A8;&#x751F;&#x6210;](../../.gitbook/assets/xxxiv-often-use-a-8.gif)

> * 如图所示，phpdoc的自动生成

## 快速找到当前文件

![&#x914D;&#x7F6E; &#x5FEB;&#x901F;&#x627E;&#x5230;&#x5F53;&#x524D;&#x6587;&#x4EF6;](../../.gitbook/assets/xxxiv-often-use-a-9.jpg)

> * 如图所示，可以快速找到当前文件

## 添加书签，方便查找代码

![&#x914D;&#x7F6E; &#x6DFB;&#x52A0;&#x4E66;&#x7B7E;](../../.gitbook/assets/xxxiv-often-use-a-10.jpg)

> * 快捷键F3，添加书签，再按下取消书签， 按Alt + F3 可以给书签做标记，有兴趣的可以试一下

## 滚轮控制字体大小

![&#x914D;&#x7F6E; &#x6EDA;&#x8F6E;&#x63A7;&#x5236;&#x5B57;&#x4F53;&#x5927;&#x5C0F;](../../.gitbook/assets/xxxiv-often-use-a-11.jpg)

## 滚轮控制图片大小

![&#x914D;&#x7F6E; &#x6EDA;&#x8F6E;&#x63A7;&#x5236;&#x56FE;&#x7247;&#x5927;&#x5C0F;](../../.gitbook/assets/xxxiv-often-use-a-12.jpg)

## 展示行数和方法线

![&#x914D;&#x7F6E; &#x6EDA;&#x8F6E;&#x63A7;&#x5236;&#x56FE;&#x7247;&#x5927;&#x5C0F;](../../.gitbook/assets/xxxiv-often-use-a-13.jpg)

> * 如上图红圈所示，默认是没有勾选 `Show line numbers` 显示行数的，但是我建议一般这个要勾选上。
> * 如上图红圈所示，默认是没有勾选 `Show method separators` 显示方法线的，这种线有助于我们区分开方法，所以也是建议勾选上的。

## 折叠代码

![&#x914D;&#x7F6E; &#x6298;&#x53E0;&#x4EE3;&#x7801;](../../.gitbook/assets/xxxiv-often-use-a-14.gif)

> * 使用快捷键 command + alt +T 生成折叠评论代码

## 浏览即打开，跳转到文件来源

![&#x914D;&#x7F6E; &#x6D4F;&#x89C8;&#x5373;&#x6253;&#x5F00;](../../.gitbook/assets/xxxiv-often-use-a-15.gif)

> * 上图配置为浏览即打开

![&#x914D;&#x7F6E; &#x8DF3;&#x8F6C;&#x5230;&#x6587;&#x4EF6;&#x6765;&#x6E90;](../../.gitbook/assets/xxxiv-often-use-a-16.gif)

> * 上图配置为跳转到文件来源

## tab 按钮

![&#x914D;&#x7F6E; tab &#x6309;&#x94AE;](../../.gitbook/assets/xxxiv-often-use-a-21.jpg)

> * 如上图所示，在打开很多文件的时候，默认是把所有打开的文件名 Tab 单行显示的。个人现在的习惯是使用多行，多行效率比单行高，因为单行会隐藏超过界面部分 Tab，这样找文件不方便。`Tab Limit` 表示最多展示tab的数量, 后面的单选的意思是:勾选上之后跳转新方法时，不是新开tab,而是在当前tab下打开

## 打开项目

![&#x914D;&#x7F6E; &#x6253;&#x5F00;&#x9879;&#x76EE;](../../.gitbook/assets/xxxiv-often-use-a-22.jpg)

> * 如上图标注 1 所示，勾选此选项后，启动的时候，默认会打开上次使用的项目。如果你只有一个项目的话，该功能还是很好用的，但是如果你有多个项目的话，建议还是关闭，这样启动的时候可以选择最近打开的某个项目。
> * 如上图所示，该选项是设置当我们已经打开一个项目窗口的时候，再打开一个项目窗口的时候是选择怎样的打开方式。
> * Open project in new window 每次都使用新窗口打开。
> * Open project in the same window 每次都替换当前已打开的项目，这样桌面上就只有一个项目窗口。
> * Confirm window to open project in 每次都弹出提示窗口，让我们选择用新窗口打开或是替换当前项目窗口。

## 软分行

![&#x914D;&#x7F6E; &#x8F6F;&#x5206;&#x884C;](../../.gitbook/assets/xxxiv-often-use-a-23.jpg)

> * 对于横向太长的代码我们可以进行软分行查看。软分行引起的分行效果是Phpstorm设置的，本质代码是没有真的分行的。

## 文件展示数

![&#x914D;&#x7F6E; &#x6587;&#x4EF6;&#x5C55;&#x793A;&#x6570;](../../.gitbook/assets/xxxiv-often-use-a-24.jpg)

> * 如上图箭头所示，该设置可以增加 Ctrl + E 弹出层显示的记录文件个数。

## 文件打开方式

![&#x914D;&#x7F6E; &#x6587;&#x4EF6;&#x6253;&#x5F00;&#x65B9;&#x5F0F;](../../.gitbook/assets/xxxiv-often-use-a-25.jpg)

> * 如上图标注 1 所示，该区域的后缀类型文件在 Phpstorm 中将以标注 2 的方式进行打开。
> * 如上图标注 3 所示，我们可以在 Phpstorm 中忽略某些后缀的文件或是文件夹，比如把 .idea 这个文件夹忽略。

## 添加访问浏览器

![&#x914D;&#x7F6E; &#x6DFB;&#x52A0;&#x8BBF;&#x95EE;&#x6D4F;&#x89C8;&#x5668;](../../.gitbook/assets/xxxiv-often-use-a-26.jpg)

> * 图1为添加浏览器路径地址
> * 图2为添加和删除新的浏览器
> * 图3所示设置默认浏览器。希望默认从控制台输出的链接是用测试浏览器打开，就可以这样设置。

## 文件追踪与反追踪

![&#x914D;&#x7F6E; &#x6587;&#x4EF6;&#x8FFD;&#x8E2A;&#x4E0E;&#x53CD;&#x8FFD;&#x8E2A;](../../.gitbook/assets/xxxiv-often-use-a-27.jpg)

> * 点击方法名称或者快捷键command+B 进行文件的追踪

![&#x914D;&#x7F6E; &#x6587;&#x4EF6;&#x8FFD;&#x8E2A;&#x4E0E;&#x53CD;&#x8FFD;&#x8E2A;](../../.gitbook/assets/xxxiv-often-use-a-28.jpg)

> * 点击方法名进行反追踪

![&#x914D;&#x7F6E; &#x6587;&#x4EF6;&#x8FFD;&#x8E2A;&#x4E0E;&#x53CD;&#x8FFD;&#x8E2A;](../../.gitbook/assets/xxxiv-often-use-a-29.jpg)

> * 有些可能因框架等原因会有黄色下滑线的方法Phpstorm找不到相应的文件，这时需要手工去添加方法让Phpstorm去识别,在头部注释增加可以识别
>
>   ```php
>   /**
>   * @property signing_company_biz signing_company_biz
>   */
>   ```

## 搜索任何文件

![&#x914D;&#x7F6E; &#x641C;&#x7D22;&#x4EFB;&#x4F55;&#x6587;&#x4EF6;](../../.gitbook/assets/xxxiv-often-use-a-30.jpg)

> * 搜索任何东西都可以 双击shift 进行查找

