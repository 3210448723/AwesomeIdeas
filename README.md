# AwesomeIdeas

记录一下偶尔蹦出来的一些奇怪点子（因为又菜又懒，估计都不会实现），权当抛砖引玉吧。

## chatgpt相关

### 插件

1. ~~修改多轮对话提问方式，支持引用之前的语句，使用树形或网状结构可视化定位聊天记录，使得可以随时对之前谈话的某个细节进行深入或者切换。可在[ChatGPTNextWeb/NextChat: ✨ Light and Fast AI Assistant. Support: Web | iOS | MacOS | Android | Linux | Windows (github.com)](https://github.com/ChatGPTNextWeb/NextChat)项目基础上修改。~~：[The AI Native Creation Engine · Refly](https://refly.ai/)

## 社交软件助手

1. 能够根据输入的一些qq，微信等聊天记录总结话题，并且在该语境下给出提示语（帮助不善于社交的人，避免冷场等）
2. 能够分析个人聊天特点，给出数据分析和建议

## ~~私域网站搜索引擎~~->收集比较优质的个人博客网站

1. 面向个人博客
2. github pages
3. 利用爬虫
4. 汇集常用搜索引擎

## 现有应用增强二次开发

1. 微信，qq聊天记录互转与合并
2. 第三方整合社交软件聊天记录，并且支持导出
3. 百度云链接/群组文件批量转存，绕开每次转存500文件数限制，可参考：
   1. [acheiii/BaiduFilesTransfers_Pro: 百度网盘批量转存工具——主来源copy原作者:hxz393，干的事大概为当分享根目录文件夹超非会员限制（500）开始遍历下级文件夹下所有文件进行保存 (github.com)](https://github.com/acheiii/BaiduFilesTransfers_Pro?tab=readme-ov-file)

5. 网盘间文件转存工具
6. ~~统一网盘视图查看不同网盘的文件~~：[主页 | AList](https://alist.pages.dev/)
7. 多平台同步发帖
8. 微信、QQ自动点赞
9. 微信qq表情包互转
10. 导出QQ微信表情包
11. 编写油猴脚本，为需要翻页的网页提供方向键翻页功能
12. 编写油猴脚本，使网页翻页逻辑支持从瀑布流翻页到页码翻页之间切换

## 现有网站增强开发

1. 编写支持多端同步的浏览器插件，为github，B站，csdn等不支持备注的网站的用户添加备注名等信息（再集成一个备注项，对页面中某些特定文本，提供鼠标悬浮其上时，展示说明框的功能），可参考：
   1. [gaogaotiantian/biliscope: Bilibili chrome extension to show uploader's stats (github.com)](https://github.com/gaogaotiantian/biliscope)：可以对B站用户添加备注名，可以在此基础上修改。
   2. [GitHub 用户备注插件：个性化管理关注者-CSDN博客](https://blog.csdn.net/qq_45738111/article/details/113901784)
   3. https://x.com/i/grok/share/mN9zVqRgHKlK6BrWL86MWp2ZT
   4. https://x.com/i/grok/share/d7iMgDh7dIvF0gBFhpkSiQtaR
3. 基于git lfs和github等代码托管平台，构建一个网络云盘（很奇怪的想法）
4. 借助暴力猴插件，对不支持记忆视频进度条的网站开发记录视频上次观看到的进度条，并且提供若干次具有一定间隔的进度条记录，避免忘记哪些看过哪些部分没看过（类似于B站效果）

## wordpress

1. 开发类似于[mAAdhaTTah/wordpress-github-sync：一个 WordPress 插件，用于将内容与 GitHub 仓库（或 Jekyll 站点）同步](https://github.com/mAAdhaTTah/wordpress-github-sync/)的，将wordpress站点内容和数据库自动同步到github等平台的wordpress插件

## AI集成平台

1. 开发类似于[视频行为分析系统v4.427，支持x86/arm/英特尔/英伟达/昇腾/RK3588/AMD/龙芯/Windows/Ubuntu/Centos/麒麟/UOS_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV12J4m1T7Q7)的AI模型合集系统
   1. 可添加多种领域的模型
   2. 支持多种模态
   3. 提供可视化训练和推理结果等后台展示信息
   4. 提供视频播放，支持将标注框和视频分开，在播放时再根据标注框坐标渲染（不把标注框直接画到原图上）
2. 

## 插件

1. 管理用户点击超链接后跳转新页面的策略：是在当前页面打开新页面还是在新标签页打开新页面（如果是这个的话还要选择是否切换到新打开的页面）。并且支持对不同的站点使用不同的策略配置

## 应用

1. 分割任意类型的文件，方便传输，将其组合后得到原文件的工具
2. 输入pdf论文，输出该论文所有引用文献的bibtex文件
3. 护眼应用，支持调节任意屏幕的屏幕亮度和护眼模式（支持多屏幕分别配置等高级功能）
4. 模拟手机通话和短信的APP或网页，支持接入大模型和AI语音，支持不同机型的UI界面

## linux

1. linux系统下的everything应用，提供web服务器可视化查询，可参考：
   1. linux命令行文件查找：[junegunn/fzf: :cherry_blossom: A command-line fuzzy finder (github.com)](https://github.com/junegunn/fzf)
   2. 跨平台具有用户界面的查找软件：[naaive/orange: Cross-platform local file search engine. (github.com)](https://github.com/naaive/orange)
   3. 支持多种存储的文件列表程序：[主页 | AList](https://alist.pages.dev/)
   

## windows系统工具

1. 在点击关机/睡眠/重启按钮后弹出确认对话框再次确认后再关闭，避免误操作。
2. 阻止某个目录的写入但不影响需要写入该目录的程序正常运行。
   1. [文件钩子——监听Windows文件操作_文件钩子监测-CSDN博客](https://blog.csdn.net/nicedante/article/details/109312457)
   2. [Grok3对话记录](https://x.com/i/grok/share/yEihQL1SJ0XEgLV8JS7jOVqWQ)

## 游戏

### [《哎呦胃，没逝的》](https://chatgpt.com/share/67931189-b440-8013-bd02-ba728e68b8f3)

一款以幽默和无厘头风格展现食品安全问题的模拟养成游戏。通过丰富的互动和创意工坊，玩家将体验到食品选择对健康的深远影响，同时了解CN食品安全现状，提升健康饮食意识。

> 整活主题，被封杀风险高

## 学术

> ❗未经过周密调研

### 混淆代码逆向工程（Automatic Deobfuscation）

[代码混淆需要经过很多步骤吗？如果是的话，我能否将代码混淆器每次步骤后的结果保存下来，参考stable diffusion的思想，将每步混淆结果反向（从完全混淆到完全不混淆）交给具有stable diffusion和大语言模型的类似架构，使用这两种技术来实现Automatic Deobfuscation？](https://x.com/i/grok/share/R4Mfyn8jdchyRX7AF0Q0wY2G8)

### 输入音频->生成图像

[在图像生成领域有没有根据用户上传的歌曲（音频），根据歌曲意境和歌词大意（文本）创作绘画的模型？](https://x.com/i/grok/share/klRIsxvyOEybwq5K74iE0Ey30)

> 可能随着多模态大模型发展而完善
