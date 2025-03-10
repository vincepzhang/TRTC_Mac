# 腾讯云实时音视频 TRTC SDK

_[English](README.md) | 简体中文_

## 产品介绍

腾讯实时音视频（Tencent Real-Time Communication，TRTC），将腾讯多年来在网络与音视频技术上的深度积累，以多人音视频通话和低延时互动直播两大场景化方案，通过腾讯云服务向开发者开放，致力于帮助开发者快速搭建低成本、低延时、高品质的音视频互动解决方案，[更多](https://cloud.tencent.com/document/product/647/16788)...

> TRTC SDK 支持Web、Android、iOS、Mac、Windows以及Flutter、小程序等所有主流平台， [更多平台](https://github.com/LiteAVSDK?q=TRTC_&type=all&sort=)...



## 更新日志
### **Version 10.7 @ 2022.09.20**

**新特性：**

- 全平台：云端混流支持调整每路输入流的音量，详见 [TRTCMixUser](https://cloud.tencent.com/document/product/647/79626#5934a926ba45ac0d5c9bd8632d3d44b5).soundLevel。
- 全平台：新增了 [onRemoteAudioStatusUpdated](https://cloud.tencent.com/document/product/647/79621#80ffbac8268b90337b6e8d4a8af2f997) 回调接口，可用于更好地识别和监控远端音频流状态。

**功能优化:** 

- 全平台：升级编码内核，提升屏幕分享场景的画质。
- 全平台：优化弱网下编码码控效果。

**缺陷修复:** 

- iOS：修复 iPad 部分设备采集音量较小的问题。
- Android：修复偶现连接蓝牙耳机但是声音外放的问题。
- 全平台：修复频繁进退房场景下偶现的 crash 问题。

更早期的版本更新历史请点击  [更多](https://cloud.tencent.com/document/product/647/46907)...


## 联系我们
- 如果你遇到了困难，可以先参阅 [常见问题](https://cloud.tencent.com/document/product/647/43018)；

- 如果你想了解TRTC SDK在复杂场景下的应用，可以参考[更多场景案例](https://cloud.tencent.com/document/product/647/57486)；

- 完整的 API 文档见 [SDK 的 API 文档](https://cloud.tencent.com/document/product/647/32258)；
- 如果需要售后技术支持, 你可以点击[这里](https://cloud.tencent.com/document/product/647/19906)；
- 如果发现了示例代码的 bug，欢迎提交 issue；
