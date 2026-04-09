# animate-check
基于深度学习的【动物识别】系统~2026原创+计算机毕设

## 项目介绍
本项目围绕“猫、鸡、狗、马”四类常见动物识别场景，构建了一个前后端分离的智能识别系统。前端采用 Vue3 与 Element Plus 负责交互展示，后端基于 Flask 提供 RESTful API，利用 TensorFlow 加载训练好的 ResNet50 模型完成图片分类推理。系统支持用户注册登录、JWT 鉴权、图像上传识别、识别历史分页查询与删除，以及公告查看与后台管理等完整业务流程。用户上传图片后，后端会先进行格式与大小校验，再保存到本地 `media` 目录，随后调用模型进行推理，返回最高置信度类别与全部类别概率，并持久化存储到 SQLite 数据库。

![图片](https://oa-project-storage.oss-cn-hangzhou.aliyuncs.com/d855cdc8c07c48f8bd6441411727d3a6.png)

![图片](https://oa-project-storage.oss-cn-hangzhou.aliyuncs.com/c9264f8d06ae4dea98492f4d3a7da90c.png)

![图片](https://oa-project-storage.oss-cn-hangzhou.aliyuncs.com/27f3449225fd465b904b2c9f94a6fe58.png)


## 演示视频 and 完整代码 and 安装
地址：https://www.yuque.com/ziwu/qkqzd2/pls272ooc8g7z1m9
