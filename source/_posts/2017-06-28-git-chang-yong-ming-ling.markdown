---
layout: post
title: "Git 常用命令"
date: 2017-06-28 10:29:25 +0800
comments: true
categories: git 
---
將其他分支的某個檔案合併到目前分支
```bash
$git checkout other_branch target_file
```
顯示其他分支的檔案
```bash
$git show other_branch:path
```
比較兩個 commit 的差別
```bash
$git diff revision_1:file_1 revision_2:file_2
```
