# Linux的网路配置

## 1. 网络ip的查看

- 在Windows操作系统的环境下 终端指令是ipconfig

- 在Linux的环境下是ifconfig

- ip在同一个网段才可以通讯

## 2. 网关的查看

- 点开编辑，打开虚拟网络编辑器
  
  ![](./images/Snipaste_2023-11-17_21-05-36.png)
  
  ![](./images/Snipaste_2023-11-17_21-06-03.png)

## 3.用ping来测试网络的连通

- 语法 ： ping 目的主机
  
  ![](./images/Snipaste_2023-11-17_21-09-42.png)
  
  图中代表成功发送

## 4.Linux的网络环境配置

1. 自动获取ip（但是每次得到的ip不一样）
   
   ![](./images/Snipaste_2023-11-17_21-16-29.png)
   
   ![](./images/Snipaste_2023-11-17_21-16-56.png)
   
   ![](./images/Snipaste_2023-11-17_21-17-12.png)

2. 指定ip（常用）
   
   - 直接修改配置文件来指定ip
   
   - 编辑vim /etc/sysconfig/network-scripts/ifcfg-ens33
   
   - 把ip地址配置成静态的
   1. 输入vim /etc/sysconfig/network-scripts/ifcfg-ens33指令
      
      ![](./images/Snipaste_2023-11-17_21-26-51.png)
   
   2. 更改配置
      
      ![](./images/Snipaste_2023-11-17_21-32-54.png)
   
   3. 回到虚拟机，更改配置
      
      ![](./images/Snipaste_2023-11-17_21-35-32.png)
      
      ![](./images/Snipaste_2023-11-17_21-35-43.png)
   
   4. 重启网络服务或者重启系统
      
      service network restart  / reboot
      
      然后就OK了
      
      ![](./images/Snipaste_2023-11-17_21-43-18.png)
      
      ![](./images/Snipaste_2023-11-17_21-43-48.png)

## 5.设置主机名和hosts映射

- 可以用hostname看主机名
  
  ![](./images/Snipaste_2023-11-17_21-58-55.png)

- 用vim /etc/hostname 修改（改完重启）

--------------------------------------------------------------------------------------------------

### 设置host映射

- Windows ping Linux
  
  C:\Windows\System32\drivers\etc\hosts  里改      ![](./images/Snipaste_2023-11-17_22-07-50.png)
  
  ![](./images/Snipaste_2023-11-17_22-10-38.png)

        改完就可以ping 主机名了



- Linux ping Windows

    打开 /etc/hosts文件

    ![](./images/Snipaste_2023-11-17_22-14-26.png)

    ![](./images/Snipaste_2023-11-17_22-16-49.png)

也成功ping通了

![](./images/Snipaste_2023-11-17_22-18-09.png)
