# Quick PPT 主题介绍
Quick PPT 是一款Meb主题，用于通过Mweb快速生成可以展示用的PPT

## 用你的MWeb来写PPT
Quick PPT 主题主要功能:

1. 5种页面过渡效果,8个界面主题
2. 背景图,背景视频,背景ifarme支持
3. 代码片段高亮,并支持高亮代码跳转展示
4. 全键盘绑定,并且支持触屏控制
5. 单页面属性设置,支持单页面跳转效果


# 如何安装

1. 下载这个git包，并且解压出来。
2. 在MWEB中的左侧右键点击任意一个文件夹，在弹出的对话框中点击 “编辑---设置为静态网站”
3. 再次右键点击该文件夹，点击 “编辑”按钮，在弹出的对话框中，点击”模板“那栏后面的“编辑“，选择”打开自定义模板所在的文件夹“
4. 将下载的主题文件夹复制到打开的模板文件夹内。
5. 在Mweb中文件夹右键”编辑“ --- ”模板“ 选择 Quick PPT 模板。
6. 在Mweb中文件夹右键”编辑“ --- ”高级设置“ ----”网站扩展“---”网站扩展设置“中设置相应的字段：切换效果，主题及默认高亮语言
7. 在Mweb中新建文档，在网站扩展中，设置相应的页面参数

# 使用技巧

1. 页面尽量不要太多文字
2. 闪现文本/纵向长页面设置后,尽量不要用代码块高亮功能，因为不会应用代码高亮样式
3. 可以多尝试变换主题和切换方式，有时候很有趣


# 如何使用

## 设置纵向使用视图

可以使用两个分割线来设置长页面
1. 在mweb的网站扩展中：纵向长页面设置中写入任意值
2. 在MWEB中连续使用两次 "插入分割线"功能,进行纵向页面分割（***重要***）
3. 除了在页面中插入两次"插入分割线"后,纵向页面的最后,也要以 两次"插入分割线"作为结束符,否则最后这页可能显示不出来了（***重要***）
4. 另外,在纵向长页面中,由于是单页面分割,不支持闪现文本,且使用插入代码块后不会有代码块格式.


## 设置自定义背景

可以设置自定义背景色及页面过渡效果
1. 设置背景颜色:可以使用16进制色号,色彩名称,RGB
2. 可以设置背景图:插入URL地址即可
3. 可以设置过渡效果: 如本页为 slide效果

## 代码片段高亮展示

1. 网站扩展--代码分段展示输入框内输入行号。
2. 跳转展示的写法是 [数字]|[数字]|[数字],[数字]-[数字]
3. 例如输入：1|3|4,5-7 这样就会在第一次跳转时高亮第一行，第二次第三行，第三次高亮第四行;第五至第七行


## 使用闪现文本

设置文本闪现效果后,当点击后触发展示下一条

* [ ] 首先设置网站扩展的 闪现文本,输入任意字符
* [ ] 在WEMB中插入,“任务列表”.
* [ ] 每一个任务列表的一列,就设为一次展示
* [ ] *需要注意的是,列表功能页,最好独立使用,跟其他功能可能会有冲突


# PPT 快捷键

按上下左右箭头控制页面跳转，同也可以使用空格键跳转。

按ESC键进入幻灯片概述，可以预览整体的PPT效果

按住alt键（在Linux中为ctrl），然后单击任何元素以使用zoom.js对其进行缩放，再次单击以缩小。
（注意：在Mac中使用command +单击。）



# 感谢

Quick PPT主题开发过程中遇到了很多困难，感谢 Mweb作者 [oulvhai]()的支持。


* Quick PPT主题，使用了 [reveal.js](https://github.com/hakimel/reveal.js) | zoom.js | notes 等代码库，感谢开作者