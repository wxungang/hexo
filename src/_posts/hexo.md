---
title: hexo
comments: true
tags:
  - hexo
  - 教程
categories:
  - hexo
  - 教程
date: 2017-09-03 14:51:59
---
hexo 使用备注

## 自定义布局
~~~md

---
title: {{title}}
date: {{date}}
tags:
  - input your tag1
  - input your tag2
categories:
  - categories
  - child categories
---
scaffold ：管理模板文件夹。文件名称即：模板名称。
由于相关主题中没有自定义的模板样式，所以一般自定义的模板没啥用处。当然也可以在themes 中新增自定义的样式。

建议：修改post模板的格式 或者修改主题。
当然自定义主题最好（工作量大点！）

~~~
## 外部资源的使用
### use folder （推荐使用文件夹管理）
指定一个路径
{% asset_path xml.xml This is an example doc %}
指定一个链接
{% asset_link link.txt This is an example link  %}
指定一个图片
{% asset_img img.jpg This is an example image %}


## 内部链接的跳转
### 格式
~~~md
{% post_link 文章文件名（不要后缀） 文章标题（可选） %}
~~~
### demo

{% post_link hello-world hexo的官方（辣鸡）基础教程 %}

## 数据 _data 在 theme/source 下添加无效

<% for (var link in site.data.menu) { %>
  <a href="<%= site.data.menu[link] %>"> <%= link %> </a>
<% } %>

