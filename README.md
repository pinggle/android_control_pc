安卓控制电脑

项目是2012年4月份在校时候做的一个比赛项目 
也是学习android后自己唯一做过的东西 以后就再没和android打过交道了


博文地址：
http://blog.csdn.net/lujianing2011/article/details/8967889
http://blog.csdn.net/lujianing2011/article/details/8972951

下载地址：http://download.csdn.net/detail/lujianing2011/5447591
（现在自己没android手机了，所以没办法测试项目了，就传到csdn下载里面了，留言反响还是不错的，说明是能用的）

实现功能：

  鼠标控制模式：
  鼠标的移动 鼠标左键点击 鼠标右键点击 鼠标滑轮
  文件的拖动  自定义音量键功能
  键盘输入模式：
  向电脑发送文字（中英） 回车 退格
  以及DOS下的输入 
  电脑方向键的控制 WSAD模式 和 UP DOWN LEFT RIGHT
  音量键可根据用户需求自定义设置功能
  手柄控制模式：
  横屏下 左边为控制方向 右边为操作
  可自定义 左边控制方式为鼠标控制 和 键盘控制
  右边 可自定义操作方式
  
技术点：
  多线程+网络编程
  JavaAPI的运用（调用操作系统事件）
  手机端事件响应的运用  
  多点触控的运用
  鼠标移动 手柄模式下键盘控制等的一些算法

应用场合：
	教师讲课时 不用再拘束于讲台 如PPT的控制等
	电脑的远距离控制  看电影聊天再也不用守在电脑前
	手机实现游戏手柄的功能 

未来畅想：
	物联网时代，当家用电器都可以连接网络时
	我们可以通过一个手机端 控制所有的家用电器
	
实现原理：
  网络Socket编程  + 多线程
  电脑作为服务器段 + 手机作为客户端
  电脑开启端口号
  手机连接电脑IP+端口
  手机根据不同事件 发送对应字符串
  服务器端解析字符串 调用相应的操作
  
<img src="http://static.oschina.net/uploads/space/2014/0622/224703_SugM_140593.jpg" alt="">
<img src="http://static.oschina.net/uploads/space/2014/0622/224741_fZ4F_140593.jpg" alt="">
<img src="http://static.oschina.net/uploads/space/2014/0622/224906_nEHJ_140593.jpg" alt="">
<img src="http://static.oschina.net/uploads/space/2014/0622/224920_91za_140593.jpg" alt="">

osc博客地址：http://my.oschina.net/lujianing