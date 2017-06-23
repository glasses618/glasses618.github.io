---
layout: post
title: "Ubuntu 常用命令"
date: 2017-06-08 11:21:51 +0800
comments: true
categories: ubuntu
---
解壓縮 tar.gz 檔
```bash
$tar zxvf file_name.tar.gz
```
解壓縮 tar 檔
```bash
$tar xvf file_name.tar
```
壓縮成 gz 檔
```bash
$gzip -c input_file > output_file.gz
```
解壓縮 gz 檔
```bash
$gzip -d file_name.gz
```

察看檔案完整路徑
```bash
$readlink -f [file_name]
```
搜尋檔名關鍵字
```bash
$find [path] -name "*keyword*" 
```
搜尋檔案內關鍵字
```bash
$grep -inR --exclude-dir={dir1,dir2} [keyword] [path]
```
