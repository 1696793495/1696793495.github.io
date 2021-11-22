---
layout: post
title: win11安装激活Solidworks2018
date: 2021-11-22
tags: 教程   
---


### 《Win11系统安装激活SolidWorks 2018》

#### 1.注册表，删除各项下solidworks注册表文件

- 在任务栏上的搜索框中，键入**regedit**，搜索Solidworks相关的注册表，全部删除。
- 或在左下角"开始"键处右键单击， 然后选择"运行"。在"打开："框中键入 regedit，然后选择"确定"。
- 搜索可能删除不干净，逐项查找删除。

#### 2.安装.NET Framework 3.5和4.0

- 在安装之前，通过Windows**阻止传出Internet访问，关闭防火墙**。
- 检查是否已安装.NET Framework 3.5和4.0。如果未安装.NET Framework 3.5（包括2.0），请转到“控制面板”->“程序和功能”->“打开或关闭Windows功能”->选择“ .NET Framework 3.5（包括2.0）”->重启电脑

#### 3.再次删除许可证

- SolidSQUAD\SolidWorks_Flexnet_Server \ server_remove.bat，以管理员身份运行server_remove.bat，然后等到服务“ SolidWorks Flexnet服务器”将被删除


#### 4.添加许可进Windows注册表

- 双击运行SolidSQUAD\ sw2021_network_serials_licensing.reg并确认添加信息进入Windows注册表

- 双击运行SolidSQUAD\ SolidSQUADLoaderEnabler.reg并确认添加信息进入Windows注册表


#### 5.安装许可证

- SolidSQUAD\SolidWorks_Flexnet_Server \ server_install.bat，以管理员身份运行“  server_install.bat”并等待直到新服务
  将安装并启动“ SolidWorks Flexnet服务器”

#### 6.安装SOLIDWORKS2020绿色版.exe

- 以管理员身份运行安装SOLIDWORKS2020绿色版.exe，路径不可选

#### 7.安装SOLIDWORKS2018

- 安装包自行下载，本人也有提供，正常安装步骤
- **安装不成功，多试试几次，特别是在安装路径选择之后的操作，安装路径务必记住**
- 只要安装上SOLIDWORKS2018，大概率是可以激活的

#### 8.替代许可文件

- 打开SolidSQUAD\Program Files\SOLIDWORKS Corp，**复制SOLIDWORKS Corp下的全部文件，粘贴到SOLIDWORKS2018安装路径下，文件全部替换**

#### 9.打开SOLIDWORKS2018

- 验证是否安装成功
- 若能成功激活打开会显示**接受**条款的，则教程结束

#### 10.补充：激活不成功

- 重复步骤4，即以下操作：

- 双击运行SolidSQUAD\ sw2021_network_serials_licensing.reg并确认添加信息进入Windows注册表

- 双击运行SolidSQUAD\ SolidSQUADLoaderEnabler.reg并确认添加信息进入Windows注册表

#### 11.激活文件链接

  - 百度网盘：https://pan.baidu.com/s/1BHA1krxxskYmieLS61LBsA
  - 提取码：whhw

## 如果本教程真的帮助到你，感谢三连

## 关注B站up"唐不苦Hz"，微信公众号"半刻清闲"

  <img type="image" src="https://1696793495.github.io//images/readme/bilibili.png" style="float: left; zoom: 50%;" /><img type="image" src="https://1696793495.github.io//images/readme/gongzhonghao.png" style="float: centre; zoom: 50%;" />