# CQU-JWC

![Liscence](https://img.shields.io/github/license/CQU-AI/cqu-jwc)
[![pypi](https://img.shields.io/pypi/v/cqu-jwc)](https://pypi.org/project/cqu-jwc/)
![download](https://pepy.tech/badge/cqu-jwc)
![Upload Python Package](https://github.com/CQU-AI/cqu-jwc/workflows/Upload%20Python%20Package/badge.svg)

CQU-JWC 是一个基于 Python3 的第三方重庆大学成绩查询工具。

## 特性

使用本查询工具，你可以
 - 直接生成csv格式的成绩表（可以用excel打开）
 - 无论评教与否都能查询入学以来的所有成绩
 - 查询到的数据段包括`课程编码`，`课程名称`，`成绩`，`学分`，`选修`，`课程类别`（专选，必修等），`教师`，`考试类别`，`备注`，`考试时间`
 - 开包即用，直接输入用户和密码，无需配置
 - 完美支持Mac和Linux,在Windows上也能稳定运行

## 安装和使用

1. 安装Python
2. 安装cqu-jwc：`pip install cqu-jwc`
3. 在命令行中输入`jwc`即可开始运行
4. 首次运行，需要输入学号和密码（身份证后六位）
5. 运行成功后，成绩将被保存到桌面的`成绩.csv`文件中。

帐号和密码会存储在你的电脑上，如需清除记录，可使用`jwc -r`


## 声明

1. 本程序开放源代码，可自行检查是否窃取你的信息。
2. 本程序不存储用户的帐号，密码。
3. 本程序不存储任何人的成绩，所有的数据来自于重庆大学教务网。