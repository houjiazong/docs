---
title: "云主机"
date: 2019-07-19T10:26:40+08:00
weight: 10
---

云主机(server)指云平台管理的虚拟机和裸金属服务器。

- 虚拟机: 又叫做云服务器，包括我们提供的 kvm 虚拟机、vmware、openstack 和各个公有云的虚拟机。

- 裸金属: 云平台提供物理机(baremetal)装机功能，安装完操作系统并被云平台管理的服务器称为裸金属服务器。

现在支持的主机和平台的对应关系如下：


|    类型   |          平台          |
|:---------:|:----------------------:|
|    kvm    |  onecloud 私有云虚拟机 |
| baremetal |  onecloud 私有云裸金属 |
|    esxi   |      vmware 虚拟机     |
| openstack | openstack 私有云虚拟机 |
|   zstack  |   zstack 私有云虚拟机  |
|   aliyun  |      阿里云虚拟机      |
|   qcloud  |      腾讯云虚拟机      |
|    aws    |       AWS 虚拟机       |
|   azure   |      Azure 虚拟机      |
|   huawei  |      华为云虚拟机      |
|   ucloud  |      UCloud 虚拟机     |
