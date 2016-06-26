本目录仅仅是一个测试bin文件目录：
1.remoteServer.jar是服务器的执行程序;
  可以在命令行使用 jar -jar remoteServer.jar 在PC端来启动服务器；
2.RemoteControl3.0.apk 为 android端的客户端程序，服务器程序会在主界面提供 IP 和 Port；
  我们可以在安卓手机上安装 RemoteControl3.0.apk，然后输入服务器提供的 IP 和 Port 来连接电脑。

该程序仅仅是个Demo，如果需要做的更完美，可以做下面几点：
1.映射服务器显示画面到 Android 端，这个数据量大，需要压缩，可以参考一些开源代码；
2.PC端控制手机端的通信要打通，这样可以实现双向控制。

