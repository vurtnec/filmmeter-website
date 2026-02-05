---
layout: feature
title: "LiDAR Rangefinder - Distance Measurement for Film Cameras"
feature_title: "LiDAR Rangefinder"
feature_title_zh: "LiDAR 激光测距"
feature_subtitle: "Precise distance measurement using iPhone's LiDAR sensor, inspired by Leica rangefinders"
description: "Use iPhone LiDAR for precise distance measurement with film cameras. Leica rangefinder-style UI. 用iPhone LiDAR为胶片相机精确测距。"
permalink: /features/lidar-rangefinder/
---

Film cameras with manual focus lenses require accurate distance estimation for critical sharpness -- especially at wide apertures where depth of field is razor-thin. FilmMeter's LiDAR rangefinder turns your iPhone into a precision distance measuring tool, using the same time-of-flight laser technology found in professional surveying equipment. Point your iPhone at your subject and instantly see the exact distance in meters or feet, eliminating the guesswork from zone focusing and manual focus photography.

### How iPhone LiDAR Works

The LiDAR (Light Detection and Ranging) scanner on iPhone 12 Pro and later models emits pulses of infrared laser light and measures the time each pulse takes to return after bouncing off surfaces in the scene. FilmMeter leverages Apple's ARKit framework to access this depth data in real time, providing distance measurements accurate to within centimeters at typical portrait and street photography distances. The system works reliably in low light conditions where optical rangefinders may struggle, making it ideal for indoor and evening film photography sessions.

### Leica Rangefinder-Inspired Interface

The rangefinder UI in FilmMeter pays homage to the legendary Leica M-series cameras with a split-image focusing display. The distance readout is presented in a clean, high-contrast format that echoes the precision engineering of classic German optical instruments. This design choice is not merely aesthetic -- it provides an intuitive visual reference that experienced rangefinder photographers will immediately recognize and appreciate. The display shows both the measured distance and the corresponding position on your lens's focus scale.

### Integration with Depth of Field

The LiDAR distance feeds directly into FilmMeter's [depth of field calculator](/features/depth-of-field/), automatically updating near limit, far limit, and total DOF as you aim at different subjects. This real-time integration is particularly valuable for [medium format](/features/medium-format/) shooters using Hasselblad, Mamiya, or Pentax 67 systems, where the shallower depth of field at equivalent angles of view demands more precise focusing. Combined with [precision metering](/features/light-metering/), you get a complete exposure and focus workflow without switching between apps.

### Supported Devices and Requirements

LiDAR distance measurement requires **iPhone 12 Pro, iPhone 13 Pro, iPhone 14 Pro, iPhone 15 Pro, or later Pro models** equipped with the LiDAR scanner. The feature uses ARKit and requires camera access. All distance calculations are performed locally on-device -- no internet connection is needed. On devices without LiDAR, the depth of field calculator still works with manual distance input.

---

<div lang="zh-Hans">

## LiDAR 测距原理和与胶片相机配合使用

胶片相机的手动对焦镜头需要精确的距离估算，尤其是在大光圈下景深极浅时。FilmMeter 的 LiDAR 测距功能将你的 iPhone 变成精密测距工具，利用与专业测量设备相同的飞行时间激光技术，即时显示到被摄体的精确距离（米或英尺）。

iPhone 12 Pro 及更新机型上的 LiDAR 扫描仪发射红外激光脉冲并测量反射时间，通过 ARKit 框架提供厘米级精度的实时距离数据。即使在光线不足的环境中也能可靠工作，非常适合室内和夜间胶片摄影。

测距界面的设计灵感来源于徕卡 M 系列相机的联动测距器，采用高对比度分裂影像式显示，向经典德国光学仪器的精密工程致敬。LiDAR 测得的距离会自动传入[景深计算器](/features/depth-of-field/)，实时更新景深近界、远界和总景深值。配合[精确测光](/features/light-metering/)功能，为胶片摄影提供完整的曝光和对焦工作流。

</div>
