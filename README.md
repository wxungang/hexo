# hexo

> hexo的使用、主题编写和理解
> 
> 详细文档参考官网 https://hexo.io 

## 问题
> 按照正常的文档 流学习。相关问题一时没法解决的先记录。后续整体完成之后再集中解决

- layout.ejs 是否可配置成其他 名称！

- md 文档中 的 front-matter 哪些可以配置
~~~
layout	布局	
title	标题	
date	建立日期	文件建立日期
updated	更新日期	文件更新日期
comments	开启文章的评论功能	true
tags	标签（不适用于分页）	
categories	分类（不适用于分页）	
permalink	覆盖文章网址
~~~

## 目录结构
> src 项目源目录：名称可以自定义。
~~~yml
# Directory
source_dir: src ## 
~~~
> > src/guides

针对 

> theme 主题目录 
~~~
# Extensions
## Plugins: https://hexo.io/plugins/
## Themes: https://hexo.io/themes/
theme: landscape #设置 渲染的主题
~~~
- 关于主题相关的要求参考 
>
>
>

## 主题
> https://hexo.io/zh-cn/docs/themes.html

### 基本结构
~~~
.
├── _config.yml 主题的配置文件。修改时会自动更新，无需重启服务器。
├── languages 语言文件夹。请参见 国际化 (i18n)。
├── layout  布局文件夹。用于存放主题的模板文件，决定了网站内容的呈现方式，Hexo 内建 Swig 模板引擎
├── scripts 
├── source
└── 

~~~



## 配置 _config.yml



