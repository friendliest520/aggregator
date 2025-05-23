<!--
 * @Author: wzdnzd
 * @Date: 2022-03-06 14:51:29
 * @Description: 
 * Copyright (c) 2022 by wzdnzd, All Rights Reserved.
-->

## 功能
打造免费代理池，爬一切可爬节点
> 拥有灵活的插件系统，如果目标网站特殊，现有功能未能覆盖，可针对性地通过插件实现

> 欢迎 Star 及 PR。对于质量较高且普适的爬取目标，亦可在 Issues 中列出，将在评估后选择性添加

## 使用方法
1.注册[谷歌cola](https://colab.research.google.com/)

2.在新建的笔记本中，运行以下命令以克隆项目仓库：点击code，输入以下代码
```
!git clone https://github.com/friendliest520/aggregator.git
```

3.安装依赖:点code输代码

  3.1.进入克隆项目目录：点code输入以下代码

  ```
  %cd aggregator
  ```
  3.2.安装项目所需的 Python 依赖项：点code输入以下代码
  ```
  !pip install -r requirements.txt
  ```

4.运行项目：点code输入以下代码

```
!python -u subscribe/collect.py -s
```
运行成功会出现`/content/aggregator/data/clash.yaml', '/content/aggregator/data/v2ray.txt', '/content/aggregator/data/singbox.json`三个文件

5.查看节点文件：点code输入以下代码

```
!cat /content/aggregator/data/clash.yaml
```
6.下载节点文件
```
from google.colab import files
files.download('/content/aggregator/data/clash.yaml')


```

## 免责申明
+ 本项目仅用作学习爬虫技术，请勿滥用，不要通过此工具做任何违法乱纪或有损国家利益之事
+ 禁止使用该项目进行任何盈利活动，对一切非法使用所产生的后果，本人概不负责

