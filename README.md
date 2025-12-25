# 基于Python的MediaPipe人脸面部关键点检测系统 python443

## 项目概述

本项目是基于Python的MediaPipe库开发的人脸面部关键点检测系统，它能够对图片、视频以及实时摄像头画面中的人脸进行关键点的检测与处理。

## 技术栈

- Python
- MediaPipe

## 功能模块

### 图片处理功能

- 支持的格式：PNG、JPG、JPEG、BMP、GIF
- 用户选择图片后，系统自动处理并显示结果
- 处理后的图片自动保存在`img`文件夹中

### 视频处理功能

- 支持的格式：MP4、AVI、MOV
- 可处理用户提供的本地视频文件
- 处理后的视频自动保存在`img`文件夹中

### 实时检测功能

- 支持摄像头实时人脸关键点检测
- 用户可随时启动/停止检测
- 实时显示检测结果

## 系统角色

- 用户：通过用户界面选择图片、视频或实时检测，查看检测结果

## 运行环境

用户需根据`requirements.txt`文件自行配置Python运行环境。

## 部署步骤

1. 确保Python环境配置正确，所有依赖项已安装
2. 运行`face_mesh_detection_ui.py`以启动系统

## 目录结构

```
project/
│
├── img/                    # 存储处理后的图片和视频
│
├── face_mesh_detection_ui.py    # 系统主界面启动脚本
│
└── requirements.txt        # Python环境依赖文件
```

## 核心亮点

- 高效的人脸关键点检测能力，基于MediaPipe强大的机器学习模型
- 支持多种图片和视频格式，应用广泛
- 实时检测功能，交互友好，便于用户操作使用
- 开源的技术方案，便于二次开发和扩展

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)


## 项目截图

![](https://img12.360buyimg.com/ddimg/jfs/t1/332945/38/16907/75504/68d41a30F3ddd8a49/ec4a5bdc26a5cfe8.jpg)

![](https://img11.360buyimg.com/ddimg/jfs/t1/331602/9/17011/69800/68d41a30F7de8c0fe/a1a7fd1b81de20c5.jpg)
