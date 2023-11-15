# 找回root密码

1. 在虚拟机启动的时候 按下e （快一点）
   
   ![](./images/Snipaste_2023-11-15_19-13-59.png)

2. 在图中位置写init=/bin/sh ,后按快捷键 ctrl + x 进入单用户模式
   
   ![](./images/Snipaste_2023-11-15_19-18-01.png)

3. 输入mount -o remount,rw /  ,然后输入passwd 更改密码
   
   ![](./images/Snipaste_2023-11-15_19-24-08.png)

4. 输入 touch /.autorelabel  然后输入 exec /sbin/init 耐心等待重启
   
   ![](./images/Snipaste_2023-11-15_19-27-08.png)
   
   到这里就用单用户模式成功改好了密码
