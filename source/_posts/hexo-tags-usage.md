---
title: hexo tags usage
categories:
  - hexo
tags:
  - tags
abbrlink: 59482
date: 2021-06-28 15:52:09
---
## hexo-github-repo-tag
### usage
```text
{% githubrepo 'https://github.com/JoJoJotarou/hexo-github-repo-tag' %}
{% githubrepo 'tiangolo/fastapi' %}
```
{% githubrepo 'https://github.com/JoJoJotarou/hexo-github-repo-tag' %}
{% githubrepo 'tiangolo/fastapi' %}
## hexo-tag-hint
### usage
```text
# 单行
{% hint 'body_text' 'hint_text' %}
# 多行
{% hint 'body_text' 'hint_text_1st_line' 'hint_text_2nd_line' ... %}
```
- {% hint 'Hexo' 'hexo-tag-hint' %}
- {% hint 'Hexo' 'A fast, simple &' 'powerful blog framework' %}

## note tag
### usage
```text
{% note default %}
default 提示块标签
{% endnote %}

{% note primary %}
primary 提示块标签
{% endnote %}

{% note success %}
success 提示块标签
{% endnote %}

{% note info %}
info 提示块标签
{% endnote %}

{% note warning %}
warning 提示块标签
{% endnote %}

{% note danger %}
danger 提示块标签
{% endnote %}
```
{% note default %}
default 提示块标签
{% endnote %}

{% note primary %}
primary 提示块标签
{% endnote %}

{% note success %}
success 提示块标签
{% endnote %}

{% note info %}
info 提示块标签
{% endnote %}

{% note warning %}
warning 提示块标签
{% endnote %}

{% note danger %}
danger 提示块标签
{% endnote %}

## tabs tag
### usage
```text
{% tabs tab,1 %} 名字为tab，默认在第1个选项卡，如果是-1则隐藏
<!-- tab -->
**选项卡 1** 
<!-- endtab -->
<!-- tab -->
**选项卡 2**
<!-- endtab -->
<!-- tab A -->
**选项卡 3** 名字为A
<!-- endtab -->
{% endtabs %}
```
{% tabs tab,1 %} 名字为tab，默认在第1个选项卡，如果是-1则隐藏
<!-- tab -->
**选项卡 1** 
<!-- endtab -->
<!-- tab -->
**选项卡 2**
<!-- endtab -->
<!-- tab A -->
**选项卡 3** 名字为A
<!-- endtab -->
{% endtabs %}
