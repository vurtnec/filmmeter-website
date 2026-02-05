---
layout: feature
title: "Light Metering - Professional Exposure Calculator"
feature_title: "Precision Light Metering"
feature_title_zh: "专业测光"
feature_subtitle: "Professional-grade exposure measurement calibrated for film photography"
description: "FilmMeter's precision light metering uses iPhone's advanced sensors for accurate film exposure calculation. 专业测光表，支持1/3档步进，胶片相机必备。"
permalink: /features/light-metering/
---

FilmMeter transforms your iPhone into a professional-grade reflected light meter purpose-built for film photography. Using Apple's AVFoundation framework, the app reads real-time luminance data from the iPhone camera sensor and converts it into precise exposure values (EV) calibrated for analog film stocks. Unlike digital camera metering that targets 18% gray for a digital sensor's linear response, FilmMeter accounts for the unique tonal response curves of silver halide emulsions, giving you exposures that preserve shadow detail and highlight texture on film.

The exposure calculator supports **1/3 stop, 1/2 stop, and full stop increments** for aperture, shutter speed, and ISO -- matching the click-stop precision of professional film cameras from Nikon, Canon, Leica, and Hasselblad. Whether you are shooting wide open at f/1.4 for shallow depth of field portraits or stopped down to f/16 for landscape hyperfocal sharpness, FilmMeter displays the complete exposure triangle in a clean, readable interface. Lock any one variable and the app instantly recalculates the other two, letting you prioritize depth of field, motion blur, or film grain as your creative vision demands.

### Long Exposure Timer and Reciprocity Compensation

For exposures beyond one second, FilmMeter includes a built-in countdown timer with audible and haptic alerts. Long exposure film photography requires [reciprocity failure compensation](/guides/reciprocity/) because film emulsions lose sensitivity during extended exposures. FilmMeter automatically calculates the corrected exposure time based on each film stock's unique reciprocity characteristics -- Fuji Acros 100 barely needs correction up to two minutes, while Ilford FP4+ may require doubling or tripling the metered time. The timer counts down the compensated duration so you can focus on your composition instead of mental math.

### Scene-Aware Metering with AI

FilmMeter goes beyond simple reflected metering with its [AI scene detection system](/features/scene-detection/). The hybrid histogram and machine learning analysis identifies challenging lighting situations -- backlit subjects, snow scenes, night cityscapes, high-contrast stage lighting -- and suggests EV compensation adjustments before you press the shutter. This intelligence is especially valuable for slide film shooters where exposure latitude is measured in fractions of a stop.

### Complete Exposure Workflow

The light meter integrates seamlessly with FilmMeter's [depth of field calculator](/features/depth-of-field/) and [LiDAR rangefinder](/features/lidar-rangefinder/), providing a complete exposure and focus solution in one app. Combined with [film roll management](/features/film-roll-management/), every metered reading can be recorded alongside your shot notes for a complete shooting log. Browse the [film stocks database](/film-stocks/) to see which films are supported with automatic reciprocity compensation and LUT color previews.

---

<div lang="zh-Hans">

## 测光原理和使用方法

FilmMeter 利用 iPhone 先进的摄像头传感器进行实时测光，专门针对胶片摄影的特性进行了校准优化。与数码相机测光不同，FilmMeter 考虑了银盐乳剂的独特色调响应曲线，确保暗部细节和高光层次在胶片上得到完美再现。

应用支持 **1/3档、1/2档和整档步进**，完美匹配尼康、佳能、徕卡、哈苏等专业胶片相机的操作方式。曝光三角（光圈、快门速度、ISO）实时联动计算，锁定任一参数即可自动求解其余两个，让你专注于景深控制、运动模糊或颗粒感的创意选择。

长曝光模式内置倒计时器，自动计算各胶片的[倒易率失效补偿](/guides/reciprocity/)时间。配合 [AI 智能场景识别](/features/scene-detection/)，应用能自动识别逆光、雪景、夜景等复杂光线条件并建议曝光补偿值。与[景深计算器](/features/depth-of-field/)和 [LiDAR 测距仪](/features/lidar-rangefinder/)无缝集成，为胶片摄影师提供完整的测光与对焦解决方案。

</div>
