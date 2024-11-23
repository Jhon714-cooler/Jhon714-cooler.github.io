---
title: Hexo+github Action搭建博客
date: 2024-11-23 13:39:15
tags:
---
# Hexo+github Action搭建博客
### 目的
使用hexo搭建自己的博客，并且使用github的action实现线上写文档直接推送至github.io  
`前置条件`：
1.git
2.node环境
3.github基本仓库配置
## 1.搭建hexo环境

1.   npm install -g hexo-cli `or` npm install hexo 局部安装 npx hexo command
2. hexo new "title" (创建新文章) 
3. 编写md文档  
4. hexo clean 清除缓存文件 (db.json) 和已生成的静态文件 (public)    
6. hexo generate (生成静态文件)  
7. hexo deploy  本地部署
此时应可以访问该blog啦
## 2. 文档的仓库管理
由于hexo的推送会默认覆盖分支内容，所以采用一个分支写作，一个分支用于文档的静态代码的存储  
1. git
2. 
