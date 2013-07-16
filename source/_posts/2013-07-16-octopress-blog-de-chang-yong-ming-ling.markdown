---
layout: post
title: "Octopress Blog 的常用命令"
date: 2013-07-16 14:29
comments: true
categories: 
---
rake new_post["xxx"] 创建新文章，声称的md文件存放在source/_post路径下

rake preview 动态生成站点预览，地址：http://172.0.0.1:4000

rake generate 生成静态文件

rake deploy 将生成的静态文件部署到github

提交代码到git库：
git add .
git commit -m "change log"
git push origin source
