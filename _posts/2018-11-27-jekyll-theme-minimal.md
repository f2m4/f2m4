---
title:  "jekyll主题之Minimal Mistakes"
comments: true
related: true
categories: 
  - Jekyll
  - themes
---
# jekyll主题--Minimal Mistakes Jekyll theme
[github地址](https://github.com/mmistakes/minimal-mistakes)  
这是一个更新频率还算高的主题.  
已精简为主.甚至刚刚调试的时候,你会觉得这不是个主题.  
它把复杂的东西都隐藏了,流于表面的是个最最最简单的页面.  
![img](http://phguzqfjx.bkt.clouddn.com/2018-11-27-21-17-48-的屏幕截图.png)  


它是一个把减法做完以后的基础页面.功能不是没有,而是都需要自己去设置,才能初露真容.  
不要被它简单的外表所蒙骗.  
具体的配置都在_config.yml里面.  
官方教程 [地址](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/)  

## 简单的说一下
对各种语言的支持,具体查看_data/ui-text.yml 
```yaml
# 修改为中文
locale                   : "zh-CN"
# 开启搜索
search                   : true

# 作者信息,就是左侧栏的具体内容可以在这部分修改
# Site Author 
# 页脚信息设置
# Site Footer
```
_data/navigation.yml 是最上方导航栏的内容.

可以建立_pages,里面可放入mc格式文件,编写一些其它页面.  
这些页面的地址(	permalink):/filename/ 可在其它页面如此引用.  