---
layout:     post
title:      自动打鼓系统ESP32蓝牙版
subtitle:   ESP32S3 + Ableton
date:       2025-03-22
author:     WL
header-img: img/post-bg-drum.jpg
catalog: true
tags:
    - Drum
---

## Selfplay Drum 项目

- ESP32S3 + Ableton+57步进电机+推拉电磁铁+语音识别板+pwm控制模块+Mos开关电路

- 开发环境Arduino IDE,通过Ableton写歌，与Esp32s3蓝牙接口通讯  

前期的现场图片：
![](https://nibilu.oss-cn-beijing.aliyuncs.com/selfplaydrum/DrumPlayBle.jpg)  
<div style="display: flex; flex-wrap: wrap; justify-content: center;">
    <img src="https://nibilu.oss-cn-beijing.aliyuncs.com/selfplaydrum/youdu%E5%9B%BE%E7%89%8720250305125209.jpeg" style="width: 48%; margin: 1%;" />
    <img src="https://nibilu.oss-cn-beijing.aliyuncs.com/selfplaydrum/youdu%E5%9B%BE%E7%89%8720250305125219.jpeg" style="width: 48%; margin: 1%;" />
</div>
<div style="display: flex; flex-wrap: wrap; justify-content: center;">
    <img src="https://nibilu.oss-cn-beijing.aliyuncs.com/selfplaydrum/youdu%E5%9B%BE%E7%89%8720250305125226.jpeg" style="width: 48%; margin: 1%;" />
    <img src="https://nibilu.oss-cn-beijing.aliyuncs.com/selfplaydrum/youdu%E5%9B%BE%E7%89%8720250305125222.jpeg" style="width: 48%; margin: 1%;" />
</div>
<div style="position: relative; padding: 30% 45%;">
  <iframe style="position: absolute; width: 100%; height: 100%; left: 0; top: 0;" src="http://nas1.cscecxbjz.cn:12345/?launchApp=SYNO.VideoController2.Application&SynoToken=PUL4KhaCtJXak&launchParam=player_id%3Dstreaming%26browse_type%3Dfilevideo%26video_type%3Dfilevideo%26is_drive%3Dfalse%26path%3D%252Fvolume1%252F%25E4%25BF%25A1%25E6%2581%25AF%25E6%25A1%25A3%25E6%25A1%2588%25E9%2583%25A8%252FDidgeridoo%252FRhythm%2520Library%252F02BeginnerRhythmsIntroduction_2025_03_21_17_12_29_924.mp4" frameborder="no" scrolling="no"> </iframe>
  </div> 
  <iframe src="http://nas1.cscecxbjz.cn:12345/?launchApp=SYNO.VideoController2.Application&SynoToken=PUL4KhaCtJXak&launchParam=player_id%3Dstreaming%26browse_type%3Dfilevideo%26video_type%3Dfilevideo%26is_drive%3Dfalse%26path%3D%252Fvolume1%252F%25E4%25BF%25A1%25E6%2581%25AF%25E6%25A1%25A3%25E6%25A1%2588%25E9%2583%25A8%252FDidgeridoo%252FRhythm%2520Library%252F02BeginnerRhythmsIntroduction_2025_03_21_17_12_29_924.mp4" width="100%" height="500" allowfullscreen></iframe>
