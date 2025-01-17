## v1.1.0/2022-02-18
- :memo: [docs]添加行内备注信息
- :sparkles: [feature] win10emoji替换为win11emoji
- :bug: [feature]修复标题加粗文字丢失颜色的问题
- :bug: [style]修复列表下的引述块使列表竖线产生间距问题
- :bug: [feature]修复dark主题备注样式
- :bug: [feature]修复代码块行数超过100数字重叠问题

## v1.0.9/2022-02-05
- 🐛部分缺陷修复
- 💄调整标签页

## v1.0.8/2022-01-31

- 🎨重构css：把语雀提示区块、超链接图标、折叠样式的相关css单独提取出来放在style文件夹下，其他样式待以后整理
- ✨更换编辑器内的字体同时也会改变文件树、大纲字体（暂时无法动态修改菜单字体）
- 🍱link icon完善assets文件类型（没有把思源当网盘的意思（*゜ー゜*））
- 💄[已关闭的笔记本]样式
- 💄借鉴BearLight_for_SiYuan主题，增加滚动条动效
- 🐛修复light主题导出pdf、html，列表无竖线划分层次
- 🐛修复导出pdf、html不显示link icon的问题
- 🐛修复某些字体下代码块行数会错乱的问题
- 🐛修复因为思源v1.7.6 **元素无法focus导致**的：h3空标题光标错位问题、空块提示隐藏失败问题、主题特有挖空块无法翻转问题
- 🌐 统一四个主题的版本号

## v0.4.7/2022-01-13
- 💄调整标签页样式
## v0.4.6/2022-01-11
- 💄调整叶子文档的图标
- 💄修复新建文档的图标
- 🐛修复文档图标在笔记内的位置问题

## v0.4.5/2021-12-26
- 🐛修复代码块显示行号不换行时，横向滚动代码，代码会与行号重叠
- 💄滚动条加圆角

## v0.4.4/2021-12-19
- 适配思源1.5.5 alpha9

## v0.4.3/2021-12-16

- 💄引述块优化
- 💄pdf标注框右边距过大问题
- ✨语雀提示区块的kbd样式 
- ✨link icon:添加b站缩写 
- 💄行内公式字体优化: 由KaTeX_Main改为KaTeX_Math明显字小且正常许多
- ✨更改默认字体为HarmonyOS_Sans_SC
- ✨替换文档树一级文档的图标为"U+26AC"
- ✨分割线样式完善

## v0.4.2/2021-12-04
- 🐛修复面板高亮颜色的问题
- 🐛修复emoji面板选中颜色
- 💄修改引用块:改成豆瓣或者哔哩哔哩那种样式
- 💄页签修改

## v0.4.1/2021-11-28
- :sparkles: add note style
## v0.4.0/2021-11-28
- 💄语雀提示区块样式优化：对行内代码和代码块进行优化
- 🐛适应目前的索引画面

## v0.3.9/2021-11-23
- 🐛黑色主题警告颜色修改！
- 💄区分警告和正常提示色！
- 💄菜单栏加宽

## v0.3.8/2021-11-13

* 🔥取消标签hover放大效果，因为有点影响修改，改为hover更改背景色
* 🍱添加link icon
  * [科学网—NBT：牛瘤胃微生物组的 4941 个宏基因组组装基因组(MAG) - 刘永鑫的博文 (sciencenet.cn)](http://blog.sciencenet.cn/blog-3334560-1290999.html)
  * [电脑软件 - 果核剥壳 (ghxi.com)](https://www.ghxi.com/category/pcsoft)
  * [DeepL 翻译：全世界最准确的翻译](https://www.deepl.com/translator)
  * [flomo](https://flomoapp.com/mine/?memo_id=OTQ5OTcwMQ)
  * [腾讯文档 (qq.com)](https://docs.qq.com/sheet/DRXpTREZzVFlibXVY?tab=plbdhd)
  * [微信读书-正版书籍小说免费阅读 (qq.com)](https://weread.qq.com/)
* 💄把默认的超链link icon替换了，之前的icon我自己看着有点会让我忍不住补全没有添加的网站icon

## v0.3.7/2021-11-05

- 🐛 bug when collapsing quote blocks https://github.com/Achuan-2/siyuan-themes-tsundoku-light/issues/7
- 🐛 inline code block part deletes unpleasant https://github.com/Achuan-2/siyuan-themes-tsundoku-light/issues/8
- 🍱link icon add [RCSB PDB](https://www.rcsb.org/)
- optimize export style: h1,page-break-before: always

## v0.3.6/2021-10-27

* 🐛 块嵌入里的待办列表不能显示删除线
* 💄 块引悬浮固定按钮激活时改变角度

## v0.3.5/2021-10-20
- 🍱link icon添加
    - [w3school](https://www.w3school.com.cn/h.asp)
    - [张鑫旭](https://www.zhangxinxu.com/)
- 🐛修复开启代码块行号后，折叠代码后行号依然显示
- 💄行内下划线样式加粗
- 💄修复表格框线粗线不均（不知道是系统的问题还是什么问题，D大说他自己没问题）
- 💄 修复语雀提示区块不能导出

## v0.3.4/2021-10-15
* 🐛 V 姐又改列表竖线颜色变量了，造成 green 主题竖线不清楚，补下
* 💄 修改引述块 blockquote 样式，原来的边框是包裹四周的，和绝大多数的网站和软件渲染样式不一样，所以还是随大流吧。但依然保留引述块加背景色的语雀样式，毕竟我之前给引述块加四周边框也只是为了方便加背景色。这样也让引述块有引述和卡片两种功能
* 💄 引述块语雀样式加粗样式配置
* 💄 分割线优化
* 💄 列表竖线调细

## v0.3.3/2021-10-13
- 🐛border取消透明度
- 🐛文件树背景色又没了，补一下
- 🐛 前进后退disable颜色更改
- 🐛列表下代码块样式修复：1.4.2的列表竖线和我代码块冲突了，就把三个点也变成竖线了；并且列表下代码块左边的列表竖线位置也不对
- 🐛修复特殊块在列表下折叠的问题

## v0.3.2/2021-10-11
* 🐛 块引固定高度为70%改为最小高度为30
* 🐛 修复挂件折叠和其他特殊块折叠的问题
* 💄  调整标题大纲样式：各级标题固定颜色
* ✨ 优化超级块折叠
## v0.3.1/2021-10-10

* 🐛 修复引述块中列表缩进问题
* 🐛 修复面板收缩的留白问题
* 🐛提及面板向上按钮悬浮会发生抖动
* 🐛 修复列表内的引述块在嵌套列表缩进问题
* ✨ 优化超链接换行
* 💄 取消light主题引述块的box-shadow

## v0.3.0 引入语雀提示块样式/2021-10-08

* ✨ 块折叠显示优化，引入语雀提示块, [使用介绍](https://www.yuque.com/achuan-2/siyuan/obxpvr)
* 🐛 修复对二级标题折叠的问题
* 🐛 完善点击图片块显示阴影的逻辑
* ✨ 块折叠显示优化
  * 段落块折叠只显示Text
  * 引述块折叠只显示Blockquote
## v0.2.9 块折叠显示优化/2021-10-06
* ✨ 块折叠显示优化，折叠块前添加icon
  * 表格折叠优化：只显示表头
  * 代码折叠优化，不显示内容，只显示语言和复制按钮
  * 标题折叠优化：字体大小不变
  * 嵌入块折叠：隐藏全部内容
  * 图片折叠优化：只显示 Image
  * 公式块、脑图、视频、音频、Iframe、Mermaid、Flowchart等块折叠优化：显示对应名字
  * 🐛已知问题：超级块折叠没有优化，因为技术有限，搞不动
* 🔥表格取消默认居中
* ✨块引固定高度为70%
## v0.2.8/2021-10-04
* 💄 调低空行提示透明度
* 🐛 修复嵌入块的问题

## v0.2.7/2021-10-02

* 区分大纲下各级标题，添加大纲标题图标悬浮放大效果提醒用户图标可以预览标题
* 笔记本样式强调
* 嵌入块上下块间距调整

## v0.2.6/2021-09-30

* 💄 pdf矩形选框增加border宽度
* 🐛修复空列表提示嵌套问题

## v.2.5/2021-09-27

* ✨ distinguish parent doc and no-child doc, canel the hidden effect of arrow and dot before doc 
* 🍱add vscode link icon
* 💄adjust opacity for link icon in completed task list
* 💄add background color when mouse hovering new file icon
* 💄add placeholder text "To-do" for empty task list, placeholder text"List" for empty ordered or unordered list like notion
* 📝 readme
  * change to English
  * add Yuque link
## v0.2.4/2021-09-26
* ✨ change new file icon
* 🍱 add new link icons
* 💄 optimize the size of file icons

## v0.2.3/2021-09-25
* 🍱 add new link icons
* ✨ net hyperlink default icon
* 💄 add border for inline-code
* 💄 increase kbd font size

## v0.2.2/2021-09-24

* ✨ add link icon!
* ✨ add local protocol icon!
* 🐛 fix deleting problem of tag 

## v0.2.1/2021-09-23

* 💄 pdf标注微调：调整光标选中文本样式
* 💄 pdf标注微调：减小pdf标注时弹窗阴影
* 💄 pdf标注微调：调整pdf颜色批注配色
* 💄 pdf页面增加纹理效果
* 💄 tag 取消后面的#号标识，调整颜色

## v0.2.0/2021-09-21

* 💄图片 hover 加阴影
* 🔥pdf 双链取消 🔖前缀

## v0.1.9/2021-09-20

* 🔥 取消嵌入块负margin
* 💄 更改文件树悬浮高亮颜色
* 💄 更改设置链接颜色

## v0.1.8/2021-09-19

* 💄 调整块嵌入内边距和外边距
* 🐛 修复行内代码设置为inline-flex的问题

## v0.1.7/2021-09-18

* 💄更改双链和pdf双链样式
* 📸 update preview.png

## v0.1.6/2021-09-17

* 🎨完善自定义属性，添加key为f的简写
* ✏完善Readme
* 🐛 区分侧栏聚焦和未聚焦状态

## v0.1.5/ 2021-09-15

* 🐛 修复块引用文字是inline-block的问题：过长会整个另起一行
* 🐛再次修修复h3标题鼠标选中有问题
* 🐛再次修复h3空行提示光标位置错位问题
* 💄 更改pdf双链标注配色，参考了BookxNote Pro
* 💄 调整编辑器标注颜色样式
* 💄 调整pdf双链标注颜色弹窗样式
* 💄 Green主题空行提示颜色调整
* 💄 Green主题自定义颜色调整
* 💄 调整pdf双链样式与块引用区别

## v0.1.4 / 2021-09-11

* 💄 标签页样式调整：去掉标签页的border-bottom，去掉第一个标签页的左上border-radius
* 💄 添加背景纹理
* 💄 更改待办列表样式

## v0.1.3 / 2021-09-07
* 🐛 修复编辑时大纲标题闪烁
* 💄 文档图标标题上方针对win10 emoji进行大小调整
* 🐛 修复blockquote内标题的左间距过大问题
* 💄 标题加粗样式优化

## v0.1.2 / 2021-09-05

* 💄 Change the label style: wrap both sides with # marks
* 💄 Make the bold style of the blockquote obvious

## v0.1.1 / 2021-08-30

* 💄 调整自定义emoji大小，适配 win10emoji大小
* 💄 隐藏 twemoji 中一些啰嗦的 emoji，适配 win10 emoji

## v0.1.0 / 2021-08-28

* 🐛 Fix h3 mouse click problem
* 🐛 Fix table location in preview mode

## v0.0.9 / 2021-08-27

* 🐛 Fix h3 display in Embeded Block

## v0.0.8 / 2021-08-26

* 💄 Optimize custom-emoji display
* 💄 Cancel img shadow

## v0.0.7 / 2021-08-25

* 💄 Optimize the style of closed notebooks
* 💄 Optimize blockquote style
* 🐛 Fix 挖空 style can't not hide inline elements

## v0.0.6/2021-08-22

* 💄 光标选中文本样式
* 💄 文档标签样式调整
* 💄 菜单样式增高
* 💄 菜单增加圆角

## v0.0.5/2021-08-21

* 💄去掉h2标题下划线
* 💄鼠标悬浮文档名、文档图标等其他图标放大动效
* 📸更新preview.png
* 🐛修复对设置、搜索弹窗的动画效果造成的块标移动

## v0.0.4/2021-08-18

* 💄调整行内代码位置
* 💄调整kbd标签

## v0.0.2/2021-08-17

* ✨补充标题折叠不改变大小，h3左侧横线重实现
* 💄更改按钮颜色
* 💄更改设置select按钮颜色
* 💄修改选中块和鼠标划选区域颜色
* 💄调整按钮悬浮提示文字

## v0.0.1/2021-08-17

* 🎉Tsundoku Light的护眼版本

