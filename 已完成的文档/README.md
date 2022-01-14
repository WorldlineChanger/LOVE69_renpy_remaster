# 贡献及源码食用指北

（——引自[首页Readme](https://github.com/luckykeeper/LOVE69_renpy_remaster)）

欢迎您前来让本项目变的更好&学习，下面简单介绍一下如何康~~本项目的代码~~我的胡言乱语

（Luckykeeper:第一次参与汉化工作，日语渣渣，主催&程序&美工&翻译&校对&润色&项目组网站基本上都是我一个人包的，测试也有参与，狂肝不易，还望轻喷😅）

讨论、聊天、提问、凑热闹、翻译纠正、提改进建议等……请移步 Issues ：[看已有条目](https://github.com/luckykeeper/LOVE69_renpy_remaster/issues) ； [发新贴](https://github.com/luckykeeper/LOVE69_renpy_remaster/issues/new)

那么，就赶快来介绍一下吧~

目前本项目的目录结构非常简单，`images` 文件夹下是本页展示的图片，`已完成的文档` 是程序的脚本，里面有如下文件（后面还会增加文件，但是没有新增的形式了）：

>已完成的文档
>
>│  OP歌词及翻译.md ——（OP的歌词整理及翻译，OP还没做）
>
>│
>
>├─bgm定义 ——（.rpy 都是 Ren'Py 的文件，别担心，语法非常简单，一看就懂![huaji](https://cdn.jsdelivr.net/gh/luckykeeper/LuckyBlog_RS@main/face/huaji.aqdzo604ncs.png)）
>
>│      bgm.rpy
>
>│
>
>├─人物表——（定义出场人物的显示名称和立绘）
>
>│      character.rpy
>
>│
>
>├─剧本（脚本) ——（包含了文本以及控制脚本，也就是 Gal 的核心)
>
>│      scene01.rpy ——（Scene01 也就是第一幕，02就代表第二幕，以此类推）
>
>│      scene02.rpy —— （Scene01 大部分是共通线，02-15是一周目内容，16及后面是二周目内容）
>
>│      scene03.rpy
>
>│      scene04.rpy
>
>│      scene05.rpy
>
>│      scene06.rpy
>
>│      scene07.rpy
>
>│      scene08.rpy
>
>│      scene09.rpy
>
>│      scene10.rpy
>
>│      scene11.rpy
>
>│      scene12.rpy
>
>│      scene13.rpy
>
>│      scene14.rpy
>
>│      scene15.rpy
>
>│      script.rpy ——（主脚本，点击“开始游戏”之后程序的入口)
>
>│
>
>├─用户图形界面 ——（关于程序的用户界面都是在这里设定的）
>
>│      gui.rpy ——（开场动画设定脚本，打开程序)
>
>│      LOVE69_renpy_remaster_project.rpy ——（设定刚打开程序时的行为)
>
>│      options.rpy ——（关于页面，程序名称、标题，以及打包设置)
>
>│      screens.rpy ——（对话框和小人物头像的设置)
>
>│
>
>└─视频ass文件
>
>  CM with Sub.ass ——（Scene01中出现的电视CM的字幕文件)
>  
