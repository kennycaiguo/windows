windows 问题
# 关于win10的环境变量编辑器变成win7的风格的解决办法
## 找到path环境变量，点击编辑，将%SystemRoot%放到最前面，记得加';'
# 如何将一幅图片的背景变为透明
操作步骤
打开PS，打开这样图片，如下图所示
我们先在右侧图层后面，点击“锁”的图标，解锁该图片
我们再从左侧找到“魔棒工具”
然后点击“魔棒工具”，点击在该图片的背景上
这是图片就出现上图所示的虚线框，点击键盘上的“delete”
这个时候图片就变成透明色了
然后Ctrl+s，选择保存“PNG”格式
## 参考网址：https://jingyan.baidu.com/article/8275fc86adfc5e07a13cf64a.html

# 如何虚拟化物理机？
答：
1.下载Microsoft的Disk2vhd_v2.01工具
2.运行disk2vhd.exe
3.需要将镜像文件保存到一个usb硬盘，容量比物理机的硬盘要大
完成后，生成两个文件如：WIN-5OKFMRREPRH-0.VHDX和WIN-5OKFMRREPRH-1.VHDX
4.这两个文件VMware使用不了，需要virtualBox虚拟机的一个叫VBoxManage.exe的工具将其转换为vmdk文件
5.端口VMware，创建一个新虚拟机，选择使用现有磁盘，将上面转换的vmdk磁盘导入，就可以将物理机转换为虚拟机了。

# win10 将一个程序设置为开机启动：
Win10如何手动添加开机启动项
按下win+R调出运行窗口，并输入“shell:startup”即可进入开机启动文件夹。
开机启动文件夹如图所示，此时文件夹中内容为空。
如果想要添加启动项，可以将软件快捷方式移入开机启动文件夹中，比如移入“福昕阅读器”。
# <a href="https://www.jianshu.com/p/73e9c94afd4e">windows10系统开机显示Win32Bridge.Server.exe参数错误</a>
# <a href="https://blog.csdn.net/gaofenglxx/article/details/118539233">开机弹框显示IGCCTray.exe异常的修复方式</a>
# <a href="https://www.bbsmax.com/A/gVdnrLyXdW/">虚拟机ping 不通主机，主机可ping 虚拟机解决方法</a>
# <a href="https://zhuanlan.zhihu.com/p/28230165">九款免费轻量的 AutoCAD 的开源替代品推荐</a>

# <a href="https://zhuanlan.zhihu.com/p/71103917">10个免费的CAD软件网站</a>

# <a href="https://linux.cn/article-11319-1.html">Linux 上 5 个最好 CAD 软件</a>

# <a href="https://blog.csdn.net/flower4wine/article/details/17150055"> win7安装了vs2010后安装DXSDK_jun10失败</a>

# <a href="http://blog.sina.com.cn/s/blog_3f61a3230102x7hs.html">emule电驴无法连接服务器</a>

# <a href="https://segmentfault.com/a/1190000008213636">Ruby 2.x 源代码学习：解释器概述</a>

# <a href="https://zhuanlan.zhihu.com/p/179046436">电脑卡顿缓慢时别再堆内存了，正确升级顺序是这样</a>

# <a href="https://mp.weixin.qq.com/s?__biz=MzUyNzc0ODI1Nw==&mid=2247487939&idx=3&sn=d30d59f4530fa48ee517285ef18cd482&chksm=fa7b8c0dcd0c051b27246a3e8192bd3d15fc56525dfbf398aa522c991261d164d5054e1a0cd8&scene=21#wechat_redirect">Windows系统必备系统优化管理工具推荐</a>

# <a href="https://answers.microsoft.com/zh-hans/windows/forum/windows_10-windows_store/windowsapps%E6%AF%8F%E9%9A%9415%E5%88%86%E9%90%98/93298795-a75c-457d-81bf-ddbbad8a135b">WindowsApps每隔15分鐘就會跳一次参数错误信息</a>

# <a href="https://blog.51cto.com/dyc2005/1975032">获取windows7 trustedInstaller权限</a>

# <a href="https://blog.csdn.net/qq_45870740/article/details/109736101?utm_term=hbuilderx%E9%85%8D%E7%BD%AEnode&utm_medium=distribute.pc_aggpage_search_result.none-task-blog-2~all~sobaiduweb~default-1-109736101&spm=3001.4430">五分钟教你搞定在HbuilderX上搭建Node.js环境</a>

# <a href="https://blog.csdn.net/u013203733/article/details/73869911">VS2010中“转到定义”提示“未能找到…</a>  

# <a href="https://support.microsoft.com/zh-cn/office/%E6%89%93%E5%BC%80%E6%88%96%E5%85%B3%E9%97%AD%E6%8B%BC%E5%86%99%E6%A3%80%E6%9F%A5-e2805461-77d4-4832-b006-061163c8d01a">word 关闭拼写检查</a>

# <a href="https://blog.csdn.net/weixin_42831477/article/details/90173253">mongoDB-winodws zip版的安装与使用</a>

# <a href="https://blog.csdn.net/hbtj_1216/article/details/50503284">timeGetTime()函数的用法</a>
# <a href="https://www.cnblogs.com/herenzhiming/articles/5488536.html">解决shader编译错误：error X3025</a>
# <a href="https://pymlovelyq.github.io/">一.【Java】从入门SE到进阶EE教你成为java工程师的2020最新书单</a>
# <a href="https://support.microsoft.com/zh-cn/windows/%E5%85%B3%E9%97%AD-windows-%E5%AE%89%E5%85%A8%E4%B8%AD%E5%BF%83%E4%B8%AD%E7%9A%84defender-%E9%98%B2%E7%97%85%E6%AF%92%E4%BF%9D%E6%8A%A4-99e6004f-c54c-8509-773c-a4d776b77960">关闭 Windows 安全中心中的Defender 防病毒保护</a>
# <a href="https://blog.csdn.net/sunmc1204953974/article/details/38112725">Windows下安装Code::Blocks 13.12进行C/C++开发</a>

# <a href="https://blog.csdn.net/qianghaohao/article/details/51924618">Linux下源码安装CodeBlocks</a>
# <a href="https://gameinstitute.qq.com/community/detail/112785">游戏开发完整学习路线</a>
# <a href="http://202.114.32.200:8080/courseware/108403/10840311/CD1/">华中科技大学计算机网络学院计算机图形学教程</a>
# <a href="https://www.daimajiaoliu.com/code/crawler">代码交流网爬虫代码</a>
# <a href="https://www.jianshu.com/p/45cd21aae931">优化Visual Studio Code的自动补全</a>
# <a href="https://marketplace.visualstudio.com/items?itemName=nieyuyao.vscode-plugin-webgl-syntax">vscode WebGL 提示插件</a>
# <a href="https://www.paincker.com/74-android-project">74个Android开发开源项目汇总</a>
# <a href="https://blog.csdn.net/axi295309066/article/details/60954771">C/C++在Android开发中的应用</a>

# <a href="https://github.com/Tyrrrz/YoutubeDownloader">c#版本的YoutubeDownloader</a>
# <a href="https://www.microsoft.com/en-us/download/details.aspx?id=35825">下载VS012,13,15,17,19,22imageLibrary</a>
