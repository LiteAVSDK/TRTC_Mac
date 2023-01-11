# 腾讯云实时音视频 TRTC SDK

_[English](README.md) | 简体中文_

## 产品介绍

腾讯实时音视频（Tencent Real-Time Communication，TRTC），将腾讯多年来在网络与音视频技术上的深度积累，以多人音视频通话和低延时互动直播两大场景化方案，通过腾讯云服务向开发者开放，致力于帮助开发者快速搭建低成本、低延时、高品质的音视频互动解决方案，[更多](https://cloud.tencent.com/document/product/647/16788)...

> TRTC SDK 支持Web、Android、iOS、Mac、Windows以及Flutter、小程序等所有主流平台， [更多平台](https://github.com/LiteAVSDK?q=TRTC_&type=all&sort=)...

## 更新日志

### Version 10.9 @ 2023.01.09

**新特性**

- Android：增加对外置麦克风设备（比如领夹式麦克风）的音频采集支持。

**功能优化**

- 全平台：优化音画同步问题，提升视频播放平滑度。
- 全平台：优化部分弱网场景的上行延迟，提升视频通话的互动效果。
- Windows&Android：优化特定场景下设定音乐音质后易产生爆音的问题。
- iOS：优化外录屏在系统横竖屏切换时随系统方向自动转正，提升观看端的体验。
- Mac：优化 MacOS 12.3 及之后版本的录屏性能，降低 CPU 开销及内存占用。
- Android：优化少量机型在媒体音量下，插入耳机后仍存在的声音外发问题。

更早期的版本更新历史请点击  [更多](https://cloud.tencent.com/document/product/647/46907)...


## 联系我们
- 如果你遇到了困难，可以先参阅 [常见问题](https://cloud.tencent.com/document/product/647/43018)；

- 如果你想了解TRTC SDK在复杂场景下的应用，可以参考[更多场景案例](https://cloud.tencent.com/document/product/647/57486)；

- 完整的 API 文档见 [SDK 的 API 文档](https://cloud.tencent.com/document/product/647/32258)；
- 如果需要售后技术支持, 你可以点击[这里](https://cloud.tencent.com/document/product/647/19906)；
- 如果发现了示例代码的 bug，欢迎提交 issue；

>**提示:** 
> OCDemo 和 SwiftDemo仅支持MacOS 13.0 及以上版本。 