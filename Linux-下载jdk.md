# 下载jdk

1. 建议卸载原来的openjdk，并创建一个目录用来存放jdk的压缩包
   
   ![](./images/Snipaste_2023-11-18_17-11-23.png)
   
   ![](./images/Snipaste_2023-11-18_17-13-19.png)

2. 用xftp把jdk传到Linux
   
   ![](./images/Snipaste_2023-11-18_17-16-13.png)

3. 解压jdk ，并把他剪切到 /usr/java/ 目录下
   
   ![](./images/Snipaste_2023-11-18_17-18-29.png)
   
   ![](./images/Snipaste_2023-11-18_17-21-15.png)

4. 配置环境变量
   
   - 修改profile文件 vim /etc/profile
     
     先复制地址
     
     ![](D:\Linux学习之路\images\Snipaste_2023-11-18_17-26-31.png)
     
     输入vim /etc/profile 添加环境变量
     
     ![](./images/Snipaste_2023-11-18_17-33-51.png)
     
     esc 后 :wq 保存退出后
     
     source /etc/profile 保存配置 就好了
     
     ![](./images/Snipaste_2023-11-18_17-36-41.png)


