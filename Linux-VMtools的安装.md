# Linux-VMtools的安装

vmtools可以设置共享文件夹，可以开主机（Windows）和 虚拟系统之间传文件

1. **打开虚拟机点击未列出**
   
   ![](https://gitee.com/mantouwowotou/linux-learning-record/blob/master/images/2023-11-14-16-27-14-image.png)

2. **使用root登录**

3. **右键弹出光驱**  
   
   ![](\images\2023-11-14-16-36-25-image.png)

4. **在左上方虚拟机里点开wmware tools安装，如果是灰色就重启虚拟机，在开机过程点安装**
   
   ![](\images\2023-11-14-16-44-09-image.png)

5. **安装完成后，有一个VMware tools,打开它，拷贝.tar文件** 
   
   ![](\images\2023-11-14-16-46-52-image.png)

![](\images\2023-11-14-16-49-40-image.png)

6. **回到主页打开主文件夹，打开其他位置，打开计算机，打开opt** 
   
   ![](\images\2023-11-14-16-50-54-image.png)
   
   ![](\images\2023-11-14-16-53-30-image.png)
   
   ![](\images\2023-11-14-16-54-34-image.png)

7. **粘贴到里面** 
   
   ![](\images\2023-11-14-16-56-44-image.png)

8. **在桌面上打开终端,打开opt目录，里面有个VMXXX.tar.gz,解压它** 
   
   ![](\images\2023-11-14-16-58-48-image.png)

![](\images\2023-11-14-17-03-29-image.png)

9. **进入解压好的目录，有个安装包，安装即可，一路回车就安装好了(注意要提前安装gcc，可以通过 gcc -v来查看是否安装)** 
   
   ![](\images\2023-11-14-17-08-06-image.png)

![](\images\2023-11-14-17-11-47-image.png)

- 接下来测试是否可以用
  
  建立一个任意名字的文件夹，在里面放一个任意内容的txt文件
  
  ![](\images\2023-11-14-17-15-25-image.png)

- 回到虚拟机，右键虚拟机点击设置，添加刚刚创建的目录
  
  ![](\images\2023-11-14-17-18-39-image.png)

![](\images\2023-11-14-17-20-38-image.png)

- 在虚拟机系统里打开主文件夹，点击其他位置，点击计算机
  
  ![](\images\2023-11-14-17-22-48-image.png)

- 找到mnt文件夹，一路点进去就能发现我们主机共享的文件了
  
  ![](\images\2023-11-14-17-23-51-image.png)

![](\images\2023-11-14-17-24-15-image.png)

![](\images\2023-11-14-17-24-47-image.png)

到这里就成功安装好了vmtools
