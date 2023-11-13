# Linux- 虚拟机 和 centso 的下载和安装

### 1. 虚拟机的下载地址

 `https://www.vmware.com/cn/products/workstation-pro.html`

### 2. 下载试用版

### 3. 无脑式的安装（可以改一下默认的安装路径）

### 4. 激活的密钥（17的密钥）

 `MC60H-DWHD5-H80U9-6V85M-8280D` 

### 5. 下载centos

centos8 :`http://mirrors.aliyun.com/centos/8/isos/x86_64/`
![输入图片说明](https://foruda.gitee.com/images/1699868956569393733/c5ecbb90_13285130.png "屏幕截图")
   centos7 :`http://mirrors.aliyun.com/centos/7/isos/x86_64/`
![输入图片说明](https://foruda.gitee.com/images/1699868994081110695/da0959c7_13285130.png "屏幕截图")

### 6. 新建虚拟机

- 文件里新建虚拟机
  ![输入图片说明](https://foruda.gitee.com/images/1699869939867927580/1c18d831_13285130.png "屏幕截图")
- 选典型，下一步
  ![输入图片说明](https://foruda.gitee.com/images/1699870066612391042/a0a6b6b9_13285130.png "屏幕截图")
- 稍后安装操作系统
  ![输入图片说明](https://foruda.gitee.com/images/1699870141293915543/4e90f0f0_13285130.png "屏幕截图")
- 选择Linux系统，并选择红帽7的版本，下一步
  ![输入图片说明](https://foruda.gitee.com/images/1699870265952397085/a29096c8_13285130.png "屏幕截图")
- 选择个剩余容量大一点的磁盘存放虚拟机
  ![输入图片说明](https://foruda.gitee.com/images/1699870440694114204/c1a03d33_13285130.png "屏幕截图")
- 20个g够用，根据自己调整
  ![输入图片说明](https://foruda.gitee.com/images/1699870503434035687/7fedfda7_13285130.png "屏幕截图")
- 自定义设置，关闭后点击完成
  ![](https://foruda.gitee.com/images/1699870616990506159/fa8eb2e5_13285130.png "屏幕截图")
- 右键点击设置
  ![输入图片说明](https://foruda.gitee.com/images/1699870802528489860/66d06e61_13285130.png "屏幕截图")
- 选择刚才下载的centos的系统
  ![输入图片说明](https://foruda.gitee.com/images/1699870945515178454/f253f98c_13285130.png "屏幕截图")
- 开启虚拟机，*（鼠标双击屏幕，选中上面的Install CentOS 7）
  ![输入图片说明](https://foruda.gitee.com/images/1699871164464298458/0d8531b9_13285130.png "屏幕截图")
- 选择简体中文，下一步
  ![输入图片说明](https://foruda.gitee.com/images/1699871282689823235/2a143143_13285130.png "屏幕截图")
- 耐心等待，选择软件选择，选择有界面的GNOME,并选择几个好用的附加环境
  ![输入图片说明](https://foruda.gitee.com/images/1699871530045724136/8e082ff6_13285130.png "屏幕截图")

![输入图片说明](https://foruda.gitee.com/images/1699871631274863491/936db95c_13285130.png "屏幕截图")

- 到这个界面后，耐心等待，不要乱点
  ![输入图片说明](https://foruda.gitee.com/images/1699871748218547149/a5a9e7d9_13285130.png "屏幕截图")

- 等待加载完毕后，点击安装位置
  ![输入图片说明](https://foruda.gitee.com/images/1699872103375893352/b1c14801_13285130.png "屏幕截图")

- 选中我要分区后点击完成
  ![输入图片说明](https://foruda.gitee.com/images/1699872172478781049/6c7129f8_13285130.png "屏幕截图")

- 然后分区，一般来说有三个区，boot分区（一般1个G）swap分区（2个G）根分区（剩下的容量空间）
  
  - 点击＋号
    ![输入图片说明](https://foruda.gitee.com/images/1699872372002417908/956dfb79_13285130.png "屏幕截图")
    ![输入图片说明](https://foruda.gitee.com/images/1699872457691544703/59ed4148_13285130.png "屏幕截图")
  - 设备类型 为标准类型 ， 文件系统 为 ext4
    ![输入图片说明](https://foruda.gitee.com/images/1699872561105531153/86890d3d_13285130.png "屏幕截图")
  - 点击 + 号 配置 swap 文件系统为 swap
    ![输入图片说明](https://foruda.gitee.com/images/1699872643821971906/93ea5569_13285130.png "屏幕截图")
    ![输入图片说明](https://foruda.gitee.com/images/1699872662775081976/99a91401_13285130.png "屏幕截图")
  - 点击 + 号 配置 / 设备类型 为标准类型 ， 文件系统 为 ext4
    ![输入图片说明](https://foruda.gitee.com/images/1699872802454678741/ec65b956_13285130.png "屏幕截图")
    ![输入图片说明](https://foruda.gitee.com/images/1699872825565112427/ee507692_13285130.png "屏幕截图")
  - 点击完成 ， 点击接受更改
    ![输入图片说明](https://foruda.gitee.com/images/1699872916353725551/6f660533_13285130.png "屏幕截图")

- 选择网络和主机名
  ![输入图片说明](https://foruda.gitee.com/images/1699873286456324811/37c0b3fc_13285130.png "屏幕截图")

- 点击安装，配置用户名密码
  ![输入图片说明](https://foruda.gitee.com/images/1699873438722113042/17681340_13285130.png "屏幕截图")

- 等待安装即可

- 重启后，接收许可，并点击完成配置即可
  ![输入图片说明](https://foruda.gitee.com/images/1699873855634547770/eebb9392_13285130.png "屏幕截图")

- 到这里就已经安装好虚拟机和centos系统了
