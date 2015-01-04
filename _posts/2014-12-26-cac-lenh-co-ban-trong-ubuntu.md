---
layout: post
title: "Các lệnh cơ bản trong Ubuntu"
description: ""
category: ubuntu
tags: [ubuntu, linux, command line]
---
{% include JB/setup %}

#1. Kiểm tra danh sách các bản cập nhật
---
~~~ shell
sudo apt-get update
~~~
#2. Cập nhật, nâng cấp các package
---
~~~ shell
    sudo apt-get upgrade
~~~
~~~ shell
    sudo apt-get dist-upgrade
~~~
> **Tips**: Sử dụng tham số `-y` để tự động confirm.
