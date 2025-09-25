# Linux-
从安装虚拟机，远程桌面连接虚拟机，到cpp的环境搭载

# 准备Linux的开发环境
1.安装gcc 使用命令:yum -y install gcc*  
2.升级软件包:yum -y install centos-release-scl devtoolset-8-gcc*  
3.启用软件包:echo "source /opt/th/devtoolset-8/enable">>/etc/profile  
*即每次启动shell的时候会执行/etc/profile脚本*
