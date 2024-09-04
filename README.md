# ubuntu下载常用软件资源&教程 / intall_app_in_ubuntu_resource&tutorial

## 远程/Remote
- [ToDesk](https://www.todesk.com/linux.html)
- [向日葵/SunloginClient](https://sunlogin.oray.com/download/linux?type=personal)
- [zerotier](https://www.zerotier.com/download) 一种远程连接局域网外的服务器的工具 / One of tools that help remotely connect to a server outside the LAN

  TL;DR:
  ```bash
  curl -s https://install.zerotier.com | sudo bash
  sudo zerotier-cli join {codes} # Join a network
  ```

## IDE
[vscode(中文教程)](https://blog.csdn.net/qq_43561914/article/details/116804531)

## 机器人/Robotics
[ROS(鱼香ROS一键安装)](http://fishros.com/install)

## 网络/Network
- [clash安装教程(中文)](https://zhuanlan.zhihu.com/p/693754050), [clash](https://github.com/doreamon-design/clash/releases)

## 搜狗输入法（Chinese）
- [搜狗下载界面](https://shurufa.sogou.com/linux) 和 [搜狗安装指导](https://shurufa.sogou.com/linux/guide)(点击下载后会自动跳转，注意先安装依赖)

## 可拆分的终端(其中一种)/One of terminals that able to split
```bash
sudo add-apt-repository ppa:gnome-terminator
sudo apt-get update
sudo apt-get install terminator
```
