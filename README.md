## OathBreaker

[![Python3](https://img.shields.io/badge/python-2.7-green.svg?style=plastic)](https://www.python.org/)
[![Django](https://img.shields.io/badge/django-1.8.18-brightgreen.svg?style=plastic)](https://www.djangoproject.com/)
[![SaltStack](https://img.shields.io/badge/salt--api-2018.3.2-yellowgreen.svg?style=plastic)](https://www.saltstack.com/)
[![Paramiko](https://img.shields.io/badge/paramiko-2.4.1-green.svg?style=plastic)](http://www.paramiko.org/)
[![MySQL](https://img.shields.io/badge/mysql-5.1.73-brightgreen.svg?style=plastic)](https://www.mysql.com/)


----

OathBreaker是基于ESB设计思路研发的全业务开放式运维操作平台，运维人员在web界面中可以定制几乎所有的日常操作，例如脚本批量执行，文件下发，文件拉取。

旨在为运维提供一个可以集中管理、批量控制和操作分布在世界各地的大规模主机的通道。

用以提升运维团队整体操作执行效率与质量，解放运维人员双手。

在OathBreaker平台上，运维人员可自由定制和编排操作任务，实现各类运维场景的一键式自动化作业。

----

### 特性
  
1. 跨平台，支持一切unix like平台、windows平台
2. 并发执行，一组操作用于1台机器或100台机器，耗时接近
3. 可扩展性，支持无限级联、快速平行扩展
4. 安全性，按照业务分配主机，运维人员只能看到、操作属于自身业务的机器，并记录所有的操作日志
5. 稳定性，前端采用成熟的django框架、后端采用salt方案
6. 易用性，无需运维人员学习新的技术,支持所有运维操作场景的操作,提供最大化的灵活度
7. 通用性，基于ESB设计理念，前端与业务解耦，后端抽象为原子支持任意业务形态

### 架构 

![Architecture](https://github.com/hong1835/OathBreaker/blob/master/statics/img/show/architecture.png)


### 一些截图 
登录页面
![Login](https://github.com/hong1835/OathBreaker/blob/master/statics/img/show/login.PNG)

web页面执行shell脚本
![shell](https://github.com/hong1835/OathBreaker/blob/master/statics/img/show/script-shell.png)

web页面执行batch脚本
![batch](https://github.com/hong1835/OathBreaker/blob/master/statics/img/show/script-batch.png)

web页面执行python脚本
![python](https://github.com/hong1835/OathBreaker/blob/master/statics/img/show/script-python.png)

web页面执行powershell脚本
![powershell](https://github.com/hong1835/OathBreaker/blob/master/statics/img/show/shell-powershell.png)

文件上传
![upload](https://github.com/hong1835/OathBreaker/blob/master/statics/img/show/upload-file.png)

文件下载
![download](https://github.com/hong1835/OathBreaker/blob/master/statics/img/show/download-file.png)

添加脚本
![download](https://github.com/hong1835/OathBreaker/blob/master/statics/img/show/script-add.png)

编辑脚本
![download](https://github.com/hong1835/OathBreaker/blob/master/statics/img/show/script-edit.png)

脚本管理
![download](https://github.com/hong1835/OathBreaker/blob/master/statics/img/show/script-manage.png)

### Required
Django 1.8.18
django_filters 1.1.0
django_restframework 3.3.3
markdown 2.6.11

### To do
1. 任务编排
2. 页面优化
3. 用saltstack grains来收集服务器信息

