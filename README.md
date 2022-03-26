# FER230_tf2.4
人脸表情识别-基于https://arxiv.org/abs/2004.11823

## 环境配置

- tensorflow2.4（GPU RTX3090）
- CUDA11+
- cudnn8+
- kersa_vggface（使用pip豆瓣源下载）
- kersa=2.2.4（使用pip豆瓣源下载）

## 依赖说明/BUG解决

### 版本问题

https://github.com/NPilis/Facial-Expression-Recognition本身使用的是TF1.14，Kersa2.2.4，所以在使用RTX3090训练时会出现版本不匹配的问题。

解决：

参考TF与Kersa官方文档的API进行新旧版本替换



