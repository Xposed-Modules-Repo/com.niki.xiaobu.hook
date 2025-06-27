# 小布换源

[个人主页](https://github.com/niki914)

## 概述

允许 ColorOS 小布助手换源自定义大模型 API，兼容 OpenAI 协议。

Enable ColorOS Breeno Assistant to support switching to a custom large language model API compatible with the OpenAI protocol.

<div style="display: flex; justify-content: space-around;">
  <img src="https://github.com/Xposed-Modules-Repo/com.niki.xiaobu.hook/blob/main/img/p1.jpg?raw=true" alt="p1" width="200"/>
  <img src="https://github.com/Xposed-Modules-Repo/com.niki.xiaobu.hook/blob/main/img/p2.jpg?raw=true" alt="p2" width="200"/>
  <img src="https://github.com/Xposed-Modules-Repo/com.niki.xiaobu.hook/blob/main/img/p3.jpg?raw=true" alt="p3" width="200"/>
</div>

xposed api 版本： 82

小布助手兼容版本： 11.8.6 其他版本自测

源码有偿获取

---

## 已知问题：

- 由于 OPPO 官方云同步机制，自定义 API 的对话记录不能被保存在本地
- 由于 OPPO Asr 语音识别服务存在反 Hook 机制，语音识别功能在开启模块后失效

> 遇到问题? 提交 [Issue](https://github.com/Xposed-Modules-Repo/com.niki.xiaobu.hook/issues/new)
