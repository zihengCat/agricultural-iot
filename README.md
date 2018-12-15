# Agricultural IoT

## TOC

- 物联网（IoT）前端技术选型
    - 概述
    - 树莓派（Raspberry Pi）
    - ESP8266 开发版
    - OV7670 摄像头模块
    - DHT11 数字温湿度传感器
    - BMP180 数字气压传感器
    - SSM-002 雨滴传感器
- 大数据分析平台（Big Data）架构分析与设计
    - 概述
    - ElasticSearch 分布式全文搜索引擎
    - Kibana 数据分析和可视化平台
    - Logstash 轻量级日志搜集处理框架
    - Hadoop 分布式大数据存储系统
    - Spark 大数据处理通用计算引擎
- 用户级客户端（Clients）开发
    - 概述
    - Web 端
    - Android 端
    - iOS 端
- 云部署（Container）与流程自动化（CI）
    - 概述
    - 基础云服务（阿里云）
    - Redis 内存数据库
    - MariaDB 关系型数据库
    - EMQ 消息中间件
    - Docker 容器引擎
    - Kubernates 容器编排
    - Airflow 数据流自动化
    - Jenkins & GitLab 持续集成

## 物联网（IoT）前端技术选型

### 概述

物联网（IoT）前端节点是农业大棚基础数据获取的核心组件。前端检测节点包括树莓派开发板，摄像头模组，ESP8266 开发版，温湿度传感器，气压传感器，雨滴传感器。检测节点以树莓派开发板为核心，集成与 GPIO 接口兼容的各类数据采集传感器模块实现相关农业实时数据监控，使用摄像头模组实现实时影像监测。前端检测节点通过外接继电器供电，外接 Wi-Fi 网络实现数据流传输。

### 树莓派（Raspberry Pi）

树莓派（英语：Raspberry Pi），是一款基于 Linux 的单片机计算机。它由英国树莓派基金会所开发，目的是以低价硬件及自由软件促进学校的基本计算机科学教育。

树莓派配备一枚博通（Broadcom）出产的 ARM 架构 700MHz BCM2835 处理器，256MB 内存（B型已升级到512MB内存），使用SD卡当作存储媒体，且拥有一个Ethernet、两个USB接口、以及HDMI（支持声音输出）和RCA端子输出支持。树莓派面积只有一张信用卡大小，体积大概是一个火柴盒大小，可以运行游戏和进行1080P影片播放。操作系统采用开源的Linux系统：Debian、ArchLinux，能够满足基本的网络浏览、文字处理以及计算机学习的需要。

![](./images/Raspberry-Pi-Zero-1-1755x1080.jpg)

> 图： Raspberry Pi Zero W 型

![](Raspberry-Pi-Zero-Location-of-Connectors-and-ICs.png)

> 图： Raspberry Pi Zero W 硬件 ICs 示意图

### ESP8266 开发版

### OV7670 摄像头模块

### DHT11 数字温湿度传感器

### BMP180 数字气压传感器

### SSM-002 雨滴传感器

## 大数据分析平台（Big Data）架构分析与设计

### 概述

### ElasticSearch 分布式全文搜索引擎

### Kibana 数据分析和可视化平台

### Logstash 轻量级日志搜集处理框架

### Hadoop 分布式大数据存储系统

### Spark 大数据处理通用计算引擎


## 用户级客户端（Clients）开发

### 概述

### Web 端

### Android 端

### iOS 端

## 云部署（Container）与流程自动化（CI）

### 概述

### 基础云服务（阿里云）

### Redis 内存数据库

### MariaDB 关系型数据库

### EMQ 消息中间件

### Docker 容器引擎

### Kubernates 容器编排

### Airflow 数据流自动化

### Jenkins & GitLab 持续集成



