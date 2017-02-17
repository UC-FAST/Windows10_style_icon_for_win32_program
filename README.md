# Windows10_style_icon_for_win32_program
To solve the Win32 program icon in the windows10 start menu style inconsistencies and too old.

(解决win32程序的图标在windows10开始菜单中风格不一致以及过于陈旧的情况。)


【更新说明】17年2月17日
项目全面迁移至github
增加bat转exe文件工具(tools文件夹内)

【更新说明】10月23日
全部图标开启透明模式
嫌弃以前颜色杂乱就用这一个版本吧
 
透明图标的实现方式:
1.	编写bat文件启动原来的程序
2.	制作相应的icon图标文件
3.	用附带的工具转换bat为exe
4.	固定新的exe即可


【更新说明】10月14日
更新搜狗浏览器 旗鱼浏览器 Sublime_text Chrome图标
[备注]Chrome浏览器比较特殊,需要手动配置路径
增加WebStorm Safari UC 百度浏览器 Shadowsocks


【更新说明】9月11日
按照微软官方磁贴设计指南重新设计
增加 火狐图标 chrome图标 等等

图标使用说明


【Adobe图标】文件夹使用教程
1、检查文件夹链接是否正确。尝试直接打开，如果失败，请自行修改，参考帖子的教程
2、检测程序的主程序名称是否一致
   如：	
主程序：			Adobe Audition CC.exe
png图标：		Adobe Audition CC.png
xml图标描述：		Adobe Audition CC.VisualElementsManifest.xml
3、将相应的png和xml文件复制到主程序所在的文件夹。




【普通APP图标】文件夹使用教程
教程与Adobe图标相同




【office图标】文件夹使用教程
1、尝试直接打开目标目录，如果失败，请自行查找程序目录。
	office程序目录查找教程：
打开word，打开任务管理器，右击-打开文件所在的位置
 
2、将office文件夹内所有文件包括文件夹，复制 到该目录。
务必替换
 
务必提供权限
 


############################################################
【注意：替换后图标不会马上显示】
图标刷新教程：
例如studio这个app，在开始屏幕
右击他-更多-打开文件所在的位置
 
对该快捷方式进行任意重命名
 
重新打开开始屏幕，稍等片刻，即可看到效果，再次重命名修改成原来的名称即可。


若图标依然没有变动：
1、请看Adobe图标教程，仔细检查文件名。
2、或者查看帖子上的使用教程。

