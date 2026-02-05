---
layout: feature
title: "AI Scene Detection - Smart Exposure Compensation"
feature_title: "AI Scene Detection"
feature_title_zh: "AI 智能场景识别"
feature_subtitle: "Hybrid ML + histogram analysis for intelligent exposure recommendations"
description: "FilmMeter's AI scene detection uses CoreML and histogram analysis for smart exposure compensation. 智能场景识别，自动曝光补偿。"
permalink: /features/scene-detection/
---

Reflected light meters -- including the ones built into film cameras -- are calibrated to assume the scene averages to 18% gray. This assumption fails in many real-world situations: a snow-covered landscape reads as overexposed, a backlit portrait underexposes the face, and a night cityscape confuses the meter entirely. FilmMeter's AI scene detection solves this problem by identifying the type of scene you are shooting and recommending exposure compensation before you take the shot.

### Two-Phase Hybrid Detection

FilmMeter uses a sophisticated two-phase approach that balances speed with accuracy:

**Phase 1 -- Histogram Analysis (Fast):** Every frame is analyzed for luminance distribution, reflectance characteristics, and contrast ratios. This fast analysis runs continuously and identifies basic exposure challenges like high-key scenes, low-key scenes, and extreme contrast situations. The histogram analyzer detects when the scene's average reflectance deviates significantly from 18% gray and suggests initial EV compensation.

**Phase 2 -- Places365 ML Classification (Intelligent):** When additional context would improve the recommendation, FilmMeter's custom-trained CoreML model classifies the scene using a neural network trained on the Places365 dataset. This identifies specific scene types -- ski slopes, beaches, concert stages, sunsets, forests, indoor interiors -- and applies scene-specific compensation rules refined through extensive real-world testing with film.

### Scene Types and Compensation Values

The detection system recognizes dozens of scene categories and maps them to appropriate EV adjustments:

- **Snow and beach scenes**: +1.0 to +1.5 EV to prevent underexposure of bright, reflective surfaces
- **Backlit subjects**: +1.0 to +2.0 EV to preserve subject detail against bright backgrounds
- **Night and low-light scenes**: Variable compensation based on highlight-to-shadow ratio
- **Stage and concert lighting**: Spot-weighted adjustments for high-contrast performance environments
- **Portraits in open shade**: Subtle +0.5 EV for pleasing skin tone exposure on color negative film
- **Dark forests and interiors**: +0.5 to +1.0 EV to open up shadow detail

### Fully Offline and Private

All scene detection runs entirely on-device using Apple's CoreML framework. No images are uploaded to any server, no internet connection is required, and no scene data leaves your iPhone. The ML model is embedded in the app bundle and optimized for real-time inference on the Neural Engine. This means the feature works just as well in a remote mountain location with no cell service as it does in a studio with gigabit internet.

### Integration with Light Metering

Scene detection works hand-in-hand with [precision light metering](/features/light-metering/) -- the AI recommendations appear as suggested EV offsets that you can accept, modify, or ignore. This preserves your creative control while providing an intelligent safety net against common metering pitfalls. The system is especially valuable when shooting slide films like Fuji Velvia or Provia where even half a stop of exposure error can ruin a frame. Combined with [film roll management](/features/film-roll-management/), your accepted compensation values are recorded in your shooting log for post-processing reference.

---

<div lang="zh-Hans">

## 混合检测方案、场景类型和补偿值

反射式测光表默认场景平均反射率为 18% 灰，但在雪景、逆光、夜景等实际场景中这一假设经常失效。FilmMeter 的 AI 场景检测通过识别拍摄场景类型，在按下快门之前就提供曝光补偿建议。

**两阶段混合检测方案：**

- **第一阶段 -- 直方图分析（快速）**：实时分析每帧画面的亮度分布、反射率特征和对比度，检测场景平均反射率偏离 18% 灰的程度并建议初始 EV 补偿。
- **第二阶段 -- Places365 ML 分类（智能）**：利用基于 Places365 数据集训练的 CoreML 模型识别具体场景类型（雪地、海滩、舞台、日落、森林、室内等），应用经过大量胶片实拍验证的场景专用补偿规则。

**常见场景补偿值：** 雪景/沙滩 +1.0~+1.5 EV，逆光 +1.0~+2.0 EV，暗调森林/室内 +0.5~+1.0 EV。所有检测完全在设备端本地运行，无需网络连接，不上传任何图片数据。

场景检测与[精确测光](/features/light-metering/)紧密协作，AI 建议以 EV 偏移形式呈现，你可以接受、调整或忽略。配合[胶卷管理](/features/film-roll-management/)系统，补偿值会记录在拍摄日志中供后期参考。

</div>
