---
title: "用Netlify搭建Hugo"
date: 2023-06-06T18:54:07+08:00
draft: false
tags: ["Hugo"]
categories: ["我的建站历程"]
---

# 前言
众所周知，我用hexo在github pages上搭建了一个博客，但是我发现速度并不尽人意，所以我用Netlify作为我的博客sv  
另外，看见hugo这个hexo的好用的替代品，想试一试，所以顺便换成了hugo玩玩  
（另外，之前的那个博客图片挂了）

# 开始！
Hugo的[快速开始](https://www.gohugo.org/doc/overview/quickstart/)在这里，各位可以自己去看看  
Hugo不像Hexo，可以用自己的指令去部署和上传到Github，所以需要自己git push，不过其实也没有难到哪里去  
Push完之后，在Netlify里添加新网站，选择Import an existing project
![Import an existing project](https://pic.flymc.cc/i/2023/08/03/qqqhyr.png)
然后选择Deplay with Github
![Deplay with Github](https://pic.flymc.cc/i/2023/08/03/qs66v7.png)
认证完成后，选择你需要部署的仓库，我这以blog为例
![image](https://pic.flymc.cc/i/2023/08/03/qsu4wy.png)
然后按需填就行
![image](https://pic.flymc.cc/i/2023/08/03/qtt4sf.png)
部署完毕后，设置一下域名，我这里用Cloudflare代理了，Netlify的CDN速度太慢了
![image](https://pic.flymc.cc/i/2023/08/03/quz1cd.png)
到这里就好了，从Hexo转到Hugo没有什么压力，关于写文章和Hexo没有区别的~  
~~又可以继续摸鱼了~~