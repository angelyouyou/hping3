## Linux工作环境应用

​	

[TOC]

## 1.系统安装

### 1.1下载源

https://cn.ubuntu.com/download

### 1.2安装步骤

#### 1.1新建虚拟机

#### 1.2导入镜像

不要选择自动运行VM。

#### 1.3设置参数

删除autoinst.flp和autoinst.iso。

#### 1.4运行虚拟机

语言建议先设置为English(US)，后面再安装语言，防止目录中产生中文。

#### 1.5安装VM Tools

1.打开虚拟机后，右键单击下图中箭头指向的位置，在弹出的菜单中单击“安装VMware Tools（T）”选项。

![img](https://img-blog.csdn.net/20180130123409117?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3V6aGl3dXdlaXN1bg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

2.弹出如下的界面，可以看到有一个名字是VMwareTools开头的压缩包，具体名字看你虚拟机版本。

![img](https://img-blog.csdn.net/20180130123658175?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3V6aGl3dXdlaXN1bg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

3.右键单击压缩包，在弹出的界面里选择倒数第二项“提取到...”

![img](https://img-blog.csdn.net/20180130140748204?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3V6aGl3dXdlaXN1bg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

4. 弹出如下小的对话框。

   ![img](https://img-blog.csdn.net/20180130140748204?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3V6aGl3dXdlaXN1bg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

5.紧接着在弹出的对话框内选择存放文件的位置，我选择存放在桌面，单击提取。

![img](https://img-blog.csdn.net/20180130124051913?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3V6aGl3dXdlaXN1bg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

6.紧接着弹出如下对话框。

![img](https://img-blog.csdn.net/20180130140606584?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3V6aGl3dXdlaXN1bg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

7.等提取完毕，我们可以在桌面上看到解压缩的文件。

![img](https://img-blog.csdn.net/20180130141327181?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3V6aGl3dXdlaXN1bg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

8.按下CTRL+ALT+T组合键打开终端，在终端依次输入命令：

```
cd Download
cd vmware-tools-distrib/
sudo ./vmware-install.pl 
```

![img](https://img-blog.csdn.net/20180130141403311?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3V6aGl3dXdlaXN1bg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

9. 出现的所有问句我们直接按回车确认。

   ![img](https://img-blog.csdn.net/20180130141738180?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3V6aGl3dXdlaXN1bg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

10.截图如下。

![img](https://img-blog.csdn.net/20180130141956390?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3V6aGl3dXdlaXN1bg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

11.继续。

![img](https://img-blog.csdn.net/20180130142032667?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3V6aGl3dXdlaXN1bg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

12.继续。

![img](https://img-blog.csdn.net/20180130142145379?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3V6aGl3dXdlaXN1bg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

13.继续。

![img](https://img-blog.csdn.net/20180130142205909?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3V6aGl3dXdlaXN1bg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

14.继续。

![img](https://img-blog.csdn.net/20180130142229611?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3V6aGl3dXdlaXN1bg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

15.继续。

![img](https://img-blog.csdn.net/20180130142402259?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3V6aGl3dXdlaXN1bg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

16.继续。



![img](https://img-blog.csdn.net/20180130142424938?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3V6aGl3dXdlaXN1bg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)



17.继续。



![img](https://img-blog.csdn.net/20180130142449554?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3V6aGl3dXdlaXN1bg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)



18.继续。



![img](https://img-blog.csdn.net/20180130142634612?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3V6aGl3dXdlaXN1bg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)



19.继续。



![img](https://img-blog.csdn.net/20180130142705647?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3V6aGl3dXdlaXN1bg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)



20.继续。



![img](https://img-blog.csdn.net/20180130142722649?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3V6aGl3dXdlaXN1bg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)



21.继续。



![img](https://img-blog.csdn.net/20180130142743544?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3V6aGl3dXdlaXN1bg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)



22.这是执行到最后的界面。我们在命令行输入sudo reboot命令重启系统。



![img](https://img-blog.csdn.net/20180130142801538?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3V6aGl3dXdlaXN1bg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)



23.在重启后的终端输入cd /mnt/并且ls查看，如果显示hgfs文件夹，表示我们的VMware Tools安装成功。

此时可以试试从主机拖拽文件到虚拟机，是好使的。



![img](https://img-blog.csdn.net/20180130142945603?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3V6aGl3dXdlaXN1bg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)



24.下面我们建立主机和虚拟机之间的共享文件夹。单击下图红框内的中的设置按钮。



![img](https://img-blog.csdn.net/20180130142921363?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3V6aGl3dXdlaXN1bg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)



25.在弹出的界面中我们按如下箭头流程走。



![img](https://img-blog.csdn.net/20180130143317009?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3V6aGl3dXdlaXN1bg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)



26.单击添加按钮后出现如下对话框，单击下一步。



![img](https://img-blog.csdn.net/20180130143420168?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3V6aGl3dXdlaXN1bg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)



27.选择主机和虚拟机要共享的文件夹。



![img](https://img-blog.csdn.net/20180130143402165?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3V6aGl3dXdlaXN1bg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)



28.我选择了主机桌面上的名字是“gonxiang”文件夹。



![img](https://img-blog.csdn.net/20180130143550956?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3V6aGl3dXdlaXN1bg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)



29.单击完成。



![img](https://img-blog.csdn.net/20180130143727999?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3V6aGl3dXdlaXN1bg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)



30.单击确定。



![img](https://img-blog.csdn.net/20180130143753563?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3V6aGl3dXdlaXN1bg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)



31.我们可以在/mnt/hgfs目录下看到“gongxiang”文件夹。



![img](https://img-blog.csdn.net/20180130143815503?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3V6aGl3dXdlaXN1bg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

## 2.更新源的设置

### 2.1备份源列表

```
sudo cp /etc/apt/sources.list /etc/apt/sources.list.bk
```

### 2.2更改源列表属性

```
sudo chmod 777 /etc/apt/sources.list
```

### 2.1编辑源列表

```
sudo gedit /etc/apt/sources.list
```

### 2.4注释原有并更换源

```
#阿里云
deb http://mirrors.aliyun.com/ubuntu/ focal main restricted universe multiverse
deb http://mirrors.aliyun.com/ubuntu/ focal-security main restricted universe multiverse
deb http://mirrors.aliyun.com/ubuntu/ focal-updates main restricted universe multiverse
deb http://mirrors.aliyun.com/ubuntu/ focal-proposed main restricted universe multiverse
deb http://mirrors.aliyun.com/ubuntu/ focal-backports main restricted universe multiverse
deb-src http://mirrors.aliyun.com/ubuntu/ focal main restricted universe multiverse
deb-src http://mirrors.aliyun.com/ubuntu/ focal-security main restricted universe multiverse
deb-src http://mirrors.aliyun.com/ubuntu/ focal-updates main restricted universe multiverse
deb-src http://mirrors.aliyun.com/ubuntu/ focal-proposed main restricted universe multiverse
deb-src http://mirrors.aliyun.com/ubuntu/ focal-backports main restricted universe multiverse

#清华
deb https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal main restricted universe multiverse
deb https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal-updates main restricted universe multiverse
deb https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal-backports main restricted universe multiverse
deb https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal-security main restricted universe multiverse
deb https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal-proposed main restricted universe multiverse
deb-src https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal main restricted universe multiverse
deb-src https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal-updates main restricted universe multiverse
deb-src https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal-backports main restricted universe multiverse
deb-src https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal-security main restricted universe multiverse
deb-src https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal-proposed main restricted universe multiverse

#中科大
deb https://mirrors.ustc.edu.cn/ubuntu/ focal main restricted universe multiverse
deb https://mirrors.ustc.edu.cn/ubuntu/ focal-updates main restricted universe multiverse
deb https://mirrors.ustc.edu.cn/ubuntu/ focal-backports main restricted universe multiverse
deb https://mirrors.ustc.edu.cn/ubuntu/ focal-security main restricted universe multiverse
deb https://mirrors.ustc.edu.cn/ubuntu/ focal-proposed main restricted universe multiverse
deb-src https://mirrors.ustc.edu.cn/ubuntu/ focal main restricted universe multiverse
deb-src https://mirrors.ustc.edu.cn/ubuntu/ focal-updates main restricted universe multiverse
deb-src https://mirrors.ustc.edu.cn/ubuntu/ focal-backports main restricted universe multiverse
deb-src https://mirrors.ustc.edu.cn/ubuntu/ focal-security main restricted universe multiverse
deb-src https://mirrors.ustc.edu.cn/ubuntu/ focal-proposed main restricted universe multiverse
```

### 2.3执行更新

```
sudo apt update
sudo apt upgrade
sudo apt-get install build-essential
sudo apt-get install aptitude
```

### 2.4WSL重启

```
net stop LxssManager
net start LxssManager
```

## 3.基础软件安装

### 3.1系统软件

#### 3.1.1主题软件

##### 3.1.1.1gnome-tweak-tool

```
sudo apt install gnome-tweak-tool
```



#### 3.1.2安装软件

##### 3.1.2.1yum

###### 3.1.2.1.1安装

```
sudo apt install yum
```



##### 3.1.2.1aptitude

###### 3.1.2.1.1安装

```
sudo apt install aptitude
```

#### 3.1.3基础软件

##### 3.1.3.1net-tools

###### 3.1.3.1.1安装

```
sudo apt install net-tools
```

### 3.2办公软件

#### 3.2.1文字处理

##### 3.2.1.1Sublime Text

###### 3.1.3.1.1安装

```
wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -
sudo apt-get install apt-transport-https
echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list
sudo apt-get update
sudo apt-get install sublime-text
```

##### 3.2.1.2VIM

###### 3.1.3.2.1安装

```
sudo apt install vim
```

#### 3.2.2浏览器

##### 3.2.2.1Chrome浏览器

###### 3.2.2.1.1安装

```
https://www.google.cn/chrome/
```



#### 3.2.3效率软件

##### 3.2.3.1WPS

###### 3.2.3.1.1安装

```
https://linux.wps.cn/
```

##### 3.2.3.2福昕PDF阅读器

##### 3.2.3.3百度网盘

###### 3.2.3.3.1安装

```
sudo apt-get install alien
http://pan.baidu.com/download
```

##### 3.2.3.4搜狗输入法

##### 3.2.3.5Shutter截图

###### 3.2.3.5.1安装

```
sudo apt-get install shutter
```

##### 3.2.3.6rar

###### 3.2.3.6.1安装

```
sudo apt-get install rar
```

##### 3.2.3.7Typora

###### 3.2.3.6.7安装

```
# sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys BA300B7755AFCFAE
wget -qO - https://typora.io/linux/public-key.asc | sudo apt-key add -

# add Typora's repository
sudo add-apt-repository 'deb https://typora.io/linux ./'
sudo apt-get update

# install typora
sudo apt-get install typora
```



### 3.3开发软件

#### 3.3.1VS Code

##### 3.3.8.1安装

```
https://code.visualstudio.com/Download
```

##### 3.3.8.2设置中文

```

```

##### 3.3.8.3安装插件

```

```

##### 3.3.8.4设置快捷键

```

```

##### 3.3.8.5安装C/C++编译器

```

```



#### 3.3.2CMAKE

##### 3.3.8.1安装

```
sudo apt-get install cmake
```

#### 3.3.3MySQL

##### 3.3.3.1安装

```
sudo apt-get install mysql-client mysql-server
```

##### 3.3.3.1修用户密码

###### 3.3.3.1.1查看已有账户密码

```
sudo more /etc/mysql/debian.cnf 
# Automatically generated for Debian scripts. DO NOT TOUCH!
[client]
host     = localhost
user     = debian-sys-maint
password = qRmYNTXRkePMV6uH
socket   = /var/run/mysqld/mysqld.sock
[mysql_upgrade]
host     = localhost
user     = debian-sys-maint
password = qRmYNTXRkePMV6uH
socket   = /var/run/mysqld/mysqld.sock
```

###### 3.3.3.1.2修改root密码

```
sudo mysql -udebian-sys-maint -pqRmYNTXRkePMV6uH
mysql> use mysql;
mysql> flush privileges;
mysql> ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'root';
mysql> flush privileges;
```

#### 3.3.4MongoDB

##### 3.3.4.1安装

```
sudo apt-get install mongodb
```

#### 3.3.5Redis

##### 3.3.5.1安装

```
sudo apt-get install redis
```

#### 3.3.6TCL-DEV

##### 3.3.6.1安装

```
sudo apt-get install tcl-dev
```

#### 3.3.7LIB-CAP

##### 3.3.7.1安装

```
sudo apt-get install libpcap-dev
ln -sf /usr/include/pcap-bpf.h /usr/include/net/bpf.h
```

#### 3.3.8GIT

##### 3.3.8.1安装

```
sudo apt-get install git
```

#### 3.3.9JDK

##### 3.3.9.1安装

###### 3.3.9.1.1下载代码

```
https://www.java.com/zh_CN/download/help/linux_x64_install.xml
```

###### 3.3.9.1.2解压缩

```
tar -xzvf jdk-8u261-linux-x64.tar.gz
```

###### 3.3.9.1.3设置环境变量

```
sudo gedit /etc/profile
#尾部添加
export JAVA_HOME=/usr/lib/jdk/  #填写jdk目录
export JRE_HOME=${JAVA_HOME}/jre
export CLASSPATH=.:${JAVA_HOME}/lib:${JRE_HOME}/lib
export PATH=$JAVA_HOME/bin:$JRE_HOME/bin:$PATH
```

###### 3.3.9.1.4更新环境变量

```
source /etc/profile
```

###### 3.3.9.1.5验证

```
java -version
javac
```

#### 3.3.10Maven

##### 3.3.10.1安装

```
sudo apt-get install maven
```

#### 3.3.11Python

##### 3.3.11.1安装

```
sudo apt-get install python
```

#### 3.3.12Perl

##### 3.3.12.1安装

```
sudo apt-get install perl

$ curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py   # 下载安装脚本
$ sudo python get-pip.py    # 运行安装脚本
sudo python3 get-pip.py    # 运行安装脚本。
sudo apt-get install python-pip
pip --version
```

#### 3.3.13Tomcat

##### 3.3.13.1安装

###### 3.3.13.1.1下载tar.gz软件

```
https://tomcat.apache.org/download-80.cgi
```

###### 3.3.13.1.2移动至指定位置并解压

```
sudo cp apache-tomcat-8.5.31.tar.gz /usr/local/lib
sudo tar -zxvf apache-tomcat-8.5.31.tar.gz
```

###### 3.3.13.1.3打开启动脚本

```
cd /usr/local/lib/apache-tomcat-8.5.31/bin
sudo gedit startup.sh
```

###### 3.3.13.1.4编辑启动脚本

```
#在最后一行前增加如下设置
#set java environment
export JAVA_HOME=/usr/java/jdk1.8 #根据实际情况修改
export JRE_HOME=${JAVA_HOME}/jre
export CLASSPATH=.:%{JAVA_HOME}/lib:%{JRE_HOME}/lib
export PATH=${JAVA_HOME}/bin:$PATH

#tomcat
export TOMCAT_HOME=/usr/local/lib/apache-tomcat-8.5.31#根据实际情况修改
```

###### 3.3.13.1.5启动服务

```
sudo ./startup.sh
sudo ./catalina.sh run
```

###### 3.3.13.1.6验证服务

```
localhost:8080
```

### 3.4业务软件

#### 3.4.1Quagga

##### 3.4.1.1安装

```
sudo apt-get install quagga
sudo apt-get install quagga-doc
```

##### 3.4.1.2使能IPv4转发

```
sudo gedit /etc/sysctl.conf
net.ipv4.ip_forward=1
net.ipv6.ip_forward=1
```

##### 3.4.1.2拷贝配置文件

```
sudo cp /usr/share/doc/quagga-core/examples/vtysh.conf.sample /etc/quagga/vtysh.conf
sudo cp /usr/share/doc/quagga-core/examples/zebra.conf.sample /etc/quagga/zebra.conf
sudo cp /usr/share/doc/quagga-core/examples/bgpd.conf.sample /etc/quagga/bgpd.conf
sudo cp /usr/share/doc/quagga-core/examples/ospfd.conf.sample /etc/quagga/ospfd.conf
sudo cp /usr/share/doc/quagga-core/examples/ospf6d.conf.sample /etc/quagga/ospf6d.conf
sudo cp /usr/share/doc/quagga-core/examples/isisd.conf.sample /etc/quagga/isisd.conf
sudo cp /usr/share/doc/quagga-core/examples/pimd.conf.sample /etc/quagga/pimd.conf
sudo cp /usr/share/doc/quagga-core/examples/ripd.conf.sample /etc/quagga/ripd.conf
sudo cp /usr/share/doc/quagga-core/examples/ripngd.conf.sample /etc/quagga/ripngd.conf
```

##### 3.4.1.2设置权限

```
sudo chown quagga:quagga /etc/quagga/*.conf
sudo chown quagga:quaggavty /etc/quagga/vtysh.conf
sudo chmod 640 /etc/quagga/*.conf
```

##### 3.4.1.3设置日志

```
mkdir /var/log/quagga/
chown quagga:quagga /var/log/quagga/
touch /var/log/zebra.log
chown quagga:quagga/var/log/zebra.log
```

##### 3.4.1.4启动服务

```
sudo service zebra start
sudo service zebra status

sudo service vtysh start
sudo service vtysh status

sudo service bgpd start
sudo service bgpd status

sudo service pimd start
sudo service pimd status

sudo service ospfd start
sudo service ospfd status

sudo service ospf6d start
sudo service ospf6d status

sudo service isisd start
sudo service isisd status

sudo service ripd start
sudo service ripd status

sudo service ripngd start
sudo service ripngd status
```

##### 3.4.1.5登陆运行

```
vtysh
```

#### 3.4.2Flow-Tools

##### 3.4.2.1安装

```
sudo apt-get install flow-tools
```

#### 3.4.3Zabbix

##### 3.4.3.1安装

```
https://www.zabbix.com/cn/download?zabbix=5.0&os_distribution=ubuntu&os_version=20.04_focal&db=mysql&ws=nginx
```

#### 3.4.4Wireshark

##### 3.4.4.1安装

```
sudo apt-get install wireshark
sudo wireshark
```

#### 3.4.5DPDK

##### 3.4.5.1安装

```
sudo apt-get install dpdk
```

#### 3.4.6VPP

#### 3.4.7Hping3

##### 3.4.7.1下载源代码

```
git clone https://github.com/antirez/hping
```

##### 3.4.7.2安装编译依赖

```
sudo apt-get install tcl-dev
sudo apt-get install libcap-dev
ln -sf /usr/include/pcap-bpf.h /usr/include/net/bpf.h
```

##### 3.4.7.3编译运行

```
./cofigure
make [no-tcl]
sudo make install
```

#### 3.4.8GNS3

##### 3.4.8.1编译运行

```
sudo add-apt-repository ppa:gns3/ppa
sudo apt update                                
sudo apt install gns3-gui gns3-server

#If you want IOU support
sudo dpkg --add-architecture i386
sudo apt update
sudo apt install gns3-iou
```

### 3.5娱乐软件

#### 3.5.1VLC视频播放器



## 10Linux常见操作

#### 10.1基础操作

#### 10.1.1更新源

```
sudo cp /etc/apt/sources.list /etc/apt/sources.list.bak
sudo gedit /etc/apt/sources.list
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install build-essential
```

#### 10.1.2安装包操作

##### 10.1.2.1 apt

```
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install build-essential
sudo apt --fix-broken install
sudo apt-get install --fix-missing
sudo apt-get install package
sudo apt-get remove packag
sudo apt-cache search package
sudo apt-cache show package
sudo apt-get install package --reinstall
sudo apt-get -f install
sudo apt-get remove package --purge
sudo apt-get build-dep package
sudo apt-get dist-upgrade
sudo apt-cache depends package
sudo apt-cache rdepends package
sudo apt-get source package
sudo apt-get clean && sudo apt-get autoclean
sudo apt-get check
```

##### 10.1.2.2 dpkg

```
sudo dpkg -i package
```

##### 10.1.2.3 yum

```
sudo yum package
```

##### 10.1.2.4aptitude

```
sudo aptitude install package
```

##### 10.1.2.4tar压缩

```
01-.tar格式
解包：[root]$ tar xvf FileName.tar -C DirName
打包：[root]$ tar cvf FileName.tar DirName（注：tar是打包，不是压缩！）
02-.gz格式
解压1：[root]$ gunzip FileName.gz
解压2：[root]$ gzip -d FileName.gz
压 缩：[root]$ gzip FileName

03-.tar.gz格式
解压：[root]$ tar zxvf FileName.tar.gz
压缩：[root]$ tar zcvf FileName.tar.gz DirName
```



### 10.2系统操作

#### 10.2.1进入恢复模式

```
进入系统时按住shift或ESC
```

#### 10.2.2修改系统root密码

```
sudo passwd
```

#### 10.2.3查看系统进程

```
ps -ef | grep xxx
```

#### 10.2.4查看系统运行

```
sudo passwd
```

#### 10.2.4文件系统

```
tail -f -n 100 FileName.txt
```



#### 10.2.2重置网络

```
#重置网络
sudo service network-manager stop 
sudo rm /var/lib/NetworkManager/NetworkManager.state 
sudo service network-manager start

#查看网络
ifconfig -a

#配置网络
sudo ifconfig eth0 192.168.1.11 netmask 255.255.255.0
sudo route add default gw 192.168.1.1
```



### 10.3与Window之间的互访

#### 10.3.1Windows访问Linux

##### 10.3.1.1安装samba

###### 10.3.1.1.1在文件夹下进行本地网络共享

![](C:\Users\wangc\AppData\Roaming\Typora\typora-user-images\image-20200913190853852.png)



###### 10.3.1.1.2使用命令行进行按照和重置

```
apt-get update
apt-get autoremove libtdb1 --purge
apt-get install libtdb1
apt-get install samba
```

###### 10.3.1.1.3设置用户名和密码

```
[root@localhost ~]smbpasswd -a root
New SMB password:
Retype new SMB password:
```



#### 10.3.2Linux访问Windows

#### 

#### 10.4SSH登陆设置

```
sudo apt-get install openssh-client
sudo apt-get install openssh-server

sudo gedit /etc/ssh/sshd_config
Port 22 #默认即可，如果有端口占用可以自己修改
PasswordAuthentication yes #允许用户名密码方式登录
PermitRootLogin yes #允许root账户登录
sudo service ssh restart #重启ssh服务
```



#### 10.5FTP与SFTP登陆设置