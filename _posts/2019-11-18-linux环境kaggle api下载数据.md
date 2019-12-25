---
layout: mypost
title: linux环境kaggle api下载数据
categories: [python]
---

# linux环境kaggle api下载数据

登录kaggle账号，打开My Account，create NEW API Token，下载的json文件保存到.kaggle文件夹。

## linux下


```python
pip install kaggle
cd ~
mkdir .kaggle
cd ~/.kaggle/

#找到要下载数据集的页面，复制API命令
kaggle datasets download -d kmader/skin-cancer-mnist-ham10000

```

## 参考资料

> https://blog.csdn.net/w5688414/article/details/85000169
>https://blog.csdn.net/zichen_ziqi/article/details/80172295
