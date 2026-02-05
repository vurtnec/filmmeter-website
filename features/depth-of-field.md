---
layout: feature
title: "Depth of Field Calculator - DOF for Film Photography"
feature_title: "Depth of Field Calculator"
feature_title_zh: "景深计算器"
feature_subtitle: "Format-aware DOF calculations for 35mm and medium format film"
description: "Calculate depth of field for film photography with format-specific circle of confusion. 35mm and 120 format support. 胶片景深计算，支持135和120画幅。"
permalink: /features/depth-of-field/
---

Depth of field -- the range of distances in a photograph that appear acceptably sharp -- is one of the most critical creative controls in film photography. Unlike digital cameras that offer instant review, film photographers must visualize their depth of field before pressing the shutter. FilmMeter's depth of field calculator provides real-time DOF information based on your actual shooting parameters, helping you make confident focus decisions whether you are shooting wide-open portraits on Portra 400 or stopped-down landscapes on Velvia 50.

### Format-Specific Circle of Confusion

The foundation of any accurate DOF calculation is the circle of confusion (CoC), which defines the maximum acceptable blur circle diameter for a point of light. Different film formats require different CoC values because larger negatives are enlarged less for a given print size. FilmMeter uses format-specific values:

- **35mm (135 format)**: 0.029mm circle of confusion -- the standard for full-frame photography
- **120 medium format**: Larger CoC values calculated per sub-format (6x4.5, 6x6, 6x7, 6x9), reflecting the reduced enlargement ratio of medium format negatives

This means the same lens focal length, aperture, and focus distance will produce different depth of field results depending on whether you are shooting [medium format](/features/medium-format/) or 35mm -- and FilmMeter handles this automatically when you select your film format.

### Hyperfocal Distance

The hyperfocal distance is the focus point at which depth of field extends from half the hyperfocal distance to infinity -- maximizing sharpness throughout the scene. FilmMeter calculates this value in real time for your current aperture and focal length combination, making it invaluable for street photography and landscape work. Focus at the hyperfocal distance with your 35mm f/2 lens stopped down to f/8, and everything from roughly 3 meters to infinity will be acceptably sharp on 35mm film.

### Visual DOF Scale

Inspired by the depth of field markings engraved on classic Leica, Nikon, and Zeiss lenses, FilmMeter displays a visual DOF scale that shows your near focus limit, far focus limit, and total depth of field range. As you adjust aperture or focus distance -- either manually or via [LiDAR measurement](/features/lidar-rangefinder/) -- the scale updates instantly, giving you the same information as a physical lens barrel but with greater precision and real-time feedback.

### Practical Applications

Combine the DOF calculator with [precision metering](/features/light-metering/) to make informed exposure trade-offs. Need more depth of field for a group portrait? Stop down two stops and let FilmMeter recalculate your shutter speed. Shooting a [medium format](/features/medium-format/) Hasselblad and wondering how much shallower your 80mm f/2.8 will render compared to the 35mm equivalent? The calculator shows you instantly. Record your chosen settings in the [film roll management](/features/film-roll-management/) system for future reference.

---

<div lang="zh-Hans">

## 景深原理、弥散圆和超焦距

景深是照片中呈现可接受清晰度的距离范围，是胶片摄影中最重要的创意控制之一。与数码相机不同，胶片摄影师必须在按下快门之前预判景深效果。FilmMeter 的景深计算器根据实际拍摄参数提供实时景深信息。

**弥散圆（Circle of Confusion）** 是景深计算的基础。不同画幅使用不同的弥散圆值：135画幅（35mm）使用 0.029mm，120中画幅则根据具体格式（6x4.5、6x6、6x7、6x9）采用更大的弥散圆值，因为中画幅底片的放大倍率更低。FilmMeter 在你选择胶片格式后会自动切换计算参数。

**超焦距** 是使景深从超焦距的一半延伸至无穷远的对焦距离，在风光和街头摄影中极为实用。FilmMeter 根据当前光圈和焦距组合实时计算超焦距。

景深标尺的设计灵感来自徕卡、尼康和蔡司经典镜头上的景深刻度，可通过 [LiDAR 测距](/features/lidar-rangefinder/)自动更新，或手动输入对焦距离。配合[精确测光](/features/light-metering/)和[胶卷管理](/features/film-roll-management/)系统，为每次拍摄提供完整的曝光和对焦记录。

</div>
