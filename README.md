# scihub_ck

一个简版的Sci-hub可用域名检查工具

A tiny tool for checking the working domain of sci-hub



## Usage

使用方法：

`perl scihub_ck`


## Description

列表文件包括262个域名后缀供检查。运行产生的文件将保存在web文件夹内。程序运行完成后，保留大小为27kb的文件即为可用域名。

The list file contained 262 domains to check. The output file will be generated into the 'web' directory. The files with 27 kb are corresponding to the working domains.


## Working domains

> Update every 30 minutes

> Daily maintenance at 00:30

Online version is available now: https://wadauk.github.io/scihub_ck/index.html


## Versions

v1.0.0 local version

v1.0.1 add online version

v1.0.2 add pipeline shell script for local version

v1.0.3 speed up and shorten the update cycle for online version
