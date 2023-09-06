---
title: "创建 RocketMQ"
description: 
draft: false
---

## 创建步骤

创建RocketMQ集群前，您需要先创建一个VPC网络。

> 为了保障数据安全，RocketMQ集群需要运行在受管私有网络中。所以在创建一个RocketMQ集群之前，需要创建一个VPC和一个受管私有网络，受管私有网络需要加入VPC，并开启DHCP服务（默认开启）。

### 第一步：基本设置

![](../../_images/base_setup.png)

根据实际需求填写**名称**和**描述**，不影响集群的功能，版本一般建议选择最新版本。

### 第二步：网络设置

![](../../_images/network_setup.png)

出于安全考虑，所有的集群都需要部署在私有网络中，请选择自己创建的网络。

### 第三步：参数设置

![](../../_images/sevice_parameter.png)

按照实际需求配置RocketMQ集群的参数。

### 第四步：用户协议

阅读并同意云平台 AppCenter 用户协议之后，点击**提交**，即可开始部署应用。
