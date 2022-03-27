# FER230_tf2.4
人脸表情识别-基于https://arxiv.org/abs/2004.11823

## 环境配置

- tensorflow2.6（GPU RTX3090）
- CUDA=11.3
- cudnn=8.2
- kersa_vggface（使用pip豆瓣源下载）
- kersa=2.6（使用pip豆瓣源下载，可选）

## 依赖说明/BUG解决

### 版本问题

https://github.com/NPilis/Facial-Expression-Recognition

本身使用的是TF1.14，Kersa2.2.4，所以在使用RTX3090训练时会出现版本不匹配的问题。

解决：

参考TF与Kersa官方文档的API进行新旧版本替换

一些文章：

- [tensorflow2.0版本AttributeError: module 'tensorflow' has no attribute 'get_default_graph'](https://www.jianshu.com/p/c09ef6597b8b)
- 



