# CloudMeeting
About 客户端基于QT，可以传输视频，音频，同时可以传输文本。涉及信号与槽，多线程，socket通信，Tcp/IP包解析. 


基本上实现文本通信和视频通信的功能，分客户端和服务器端。
![image](https://github.com/BiT020925/CloudMeeting/assets/138146292/706b540e-8857-4533-9973-c377ba4d2bfc)
输入服务器端地址与端口，点击连接按钮就可以连接到服务器, 然后可以点击创建会议按钮或者加入会议按钮。当点击创建会议按钮时，服务器会发送一个空闲的房间号（其实就是进程号）。然后把房间号给别人，别人就可以连接服务器，加入会议
![image](https://github.com/BiT020925/CloudMeeting/assets/138146292/42690026-1020-4525-9ac3-300765a23982)
点击打开视频，就可以开启摄像头，向别人共享你的图像
![image](https://github.com/BiT020925/CloudMeeting/assets/138146292/09a967ef-8485-451e-9574-9159de88583a)
