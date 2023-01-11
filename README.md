# TRTC SDK

_[简体中文](README-zh_CN.md) | English_
## Overview

Leveraging Tencent's many years of experience in network and audio/video technologies, Tencent Real-Time Communication (TRTC) offers solutions for group audio/video calls and low-latency interactive live streaming. With TRTC, you can quickly develop cost-effective, low-latency, and high-quality interactive audio/video services. [Learn more](https://www.tencentcloud.com/document/product/647/35078).

> We offer SDKs for web, Android, iOS, macOS, Windows, Flutter, WeChat Mini Program, and [other mainstream platforms](https://github.com/LiteAVSDK?q=TRTC_&type=all&sort=).



## Changelog
### Version 10.9 @ 2023.01.09

**New features**

- Android: Added audio capture support for external microphone devices (such as lavalier microphones).

**Function optimization**

- All platform: optimize the synchronization of audio and video, and improve the smoothness of video playback.
- All platform: optimize the uplink delay in some weak network scenarios, and improve the interactive effect of video calls.
- Windows&Android: Optimized the problem of popping sound after setting the music sound quality in a specific scene.
- iOS: Optimized the external recording screen to automatically turn to the right side with the system orientation when the system switches between horizontal and vertical screens, improving the viewing experience.
- Mac: Optimize the screen recording performance of MacOS 12.3 and later versions, reducing CPU overhead and memory usage.
- Android: Optimized the sound output problem that still exists after plugging in headphones under the media volume of a small number of models.

For the release notes of earlier versions, click [More](https://www.tencentcloud.com/document/product/647/39426).


## Contact Us
- If you have questions, see [FAQs](https://www.tencentcloud.com/document/product/647/36057).

- To learn about how the TRTC SDK can be used in different scenarios, see [Sample Code](https://www.tencentcloud.com/document/product/647/42963).

- For complete API documentation, see [SDK API Documentation](https://www.tencentcloud.com/document/product/647/35119).

- Communication & Feedback   
Welcome to join our Telegram Group to communicate with our professional engineers! We are more than happy to hear from you~
Click to join: [https://t.me/+EPk6TMZEZMM5OGY1](https://t.me/+EPk6TMZEZMM5OGY1)   
Or scan the QR code   
  <img src="https://qcloudimg.tencent-cloud.cn/raw/79cbfd13877704ff6e17f30de09002dd.jpg" width="300px">    

>**Notice:** 
> OCDemo and SwiftDemo only support MacOS 13.0 and above.
