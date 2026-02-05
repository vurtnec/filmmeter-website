---
layout: feature
title: "Exposure Triangle Guide - Aperture, Shutter Speed & ISO for Film Photography"
description: "Master the exposure triangle for film photography: aperture, shutter speed, and ISO explained. Film vs digital ISO differences. 曝光三角指南：光圈、快门、ISO与胶片摄影入门。"
permalink: /guides/exposure-triangle/
---

<nav class="breadcrumb">
  <a href="{{ '/' | relative_url }}">Home</a>
  <span>/</span>
  <a href="{{ '/guides/' | relative_url }}">Guides</a>
  <span>/</span>
  <span>Exposure Triangle</span>
</nav>

<div class="feature-page-hero">
  <h1>The Exposure Triangle</h1>
  <p class="zh-subtitle" lang="zh-Hans">曝光三角 — 胶片摄影的光圈、快门与 ISO</p>
  <p>The exposure triangle is the fundamental concept in photography: three interdependent settings — <strong>aperture</strong>, <strong>shutter speed</strong>, and <strong>ISO</strong> — that together determine the exposure of your photograph.</p>
</div>

## The Three Elements / 三大要素

### 1. Aperture (光圈)

Aperture is the size of the lens opening, measured in **f-stops** (f/1.4, f/2, f/2.8, f/4, f/5.6, f/8, f/11, f/16, f/22).

- **Larger opening** (small f-number like f/1.4) = more light, **shallower** depth of field
- **Smaller opening** (large f-number like f/16) = less light, **deeper** depth of field

Each full stop doubles or halves the light:
f/1.4 → f/2 → f/2.8 → f/4 → f/5.6 → f/8 → f/11 → f/16 → f/22

<div class="bilingual-content" lang="zh-Hans">
<p><strong>光圈</strong>控制镜头进光量的大小。f 值越小（如 f/1.4），进光越多、景深越浅；f 值越大（如 f/16），进光越少、景深越深。每相邻一档光圈，进光量相差一倍。</p>
</div>

### 2. Shutter Speed (快门速度)

Shutter speed is how long the shutter stays open, measured in fractions of a second or full seconds.

- **Fast shutter** (1/1000s) = freezes motion, less light
- **Slow shutter** (1/30s, 1s, 30s) = motion blur, more light

Standard full-stop scale:
1/1000 → 1/500 → 1/250 → 1/125 → 1/60 → 1/30 → 1/15 → 1/8 → 1/4 → 1/2 → 1s → 2s → 4s ...

<div class="bilingual-content" lang="zh-Hans">
<p><strong>快门速度</strong>控制感光材料的曝光时间。快门越快（如 1/1000s），可以冻结运动、进光量少；快门越慢（如 1s），会产生运动模糊、进光量多。</p>
</div>

### 3. ISO (感光度)

ISO determines the film's sensitivity to light. In film photography, ISO is **fixed** for the entire roll — you choose it when you load the film.

- **Low ISO** (50, 100) = fine grain, less sensitive, needs more light
- **High ISO** (400, 800) = more grain, more sensitive, works in lower light

Common film ISOs: 50, 100, 160, 200, 400, 800

<div class="bilingual-content" lang="zh-Hans">
<p><strong>ISO 感光度</strong>决定胶片对光线的敏感程度。低 ISO（50/100）颗粒细腻但需要更多光线；高 ISO（400/800）颗粒较粗但适合弱光环境。与数码不同，胶片的 ISO 在装入后就固定了。</p>
</div>

---

## How They Work Together / 三者如何配合

The exposure triangle is a **balancing act**: changing one setting requires adjusting another to maintain the same exposure.

| Scenario | Aperture | Shutter | ISO | Result |
|---|---|---|---|---|
| Bright daylight portrait | f/2.8 | 1/500 | 400 | Shallow DOF, frozen subject |
| Landscape in golden hour | f/11 | 1/60 | 100 | Deep DOF, tripod recommended |
| Street photography | f/8 | 1/250 | 400 | Moderate DOF, decisive moments |
| Night long exposure | f/8 | 30s | 100 | Deep DOF, light trails |
| Indoor available light | f/1.4 | 1/30 | 800 | Very shallow DOF, handheld limit |

### The Sunny 16 Rule

A classic film photography rule of thumb: on a sunny day, set aperture to **f/16** and shutter speed to **1/ISO**.

- ISO 400 film on a sunny day: f/16 at 1/500s (nearest standard speed)
- ISO 100 film on a sunny day: f/16 at 1/125s

<div class="bilingual-content" lang="zh-Hans">
<p><strong>阳光十六法则</strong>：晴天时，光圈设为 f/16，快门设为 1/ISO。例如 ISO 400 的胶片在晴天：f/16、1/500s。这是胶片摄影中最经典的快速测光法则。</p>
</div>

---

## Film ISO vs Digital ISO / 胶片 ISO 与数码 ISO 的区别

| Aspect | Film ISO | Digital ISO |
|---|---|---|
| **Changeable?** | Fixed per roll | Adjustable per shot |
| **Grain/Noise** | Silver halide grain (organic) | Electronic noise (digital) |
| **High ISO look** | Visible grain, retained detail | Noise, potential detail loss |
| **Push/Pull** | Possible in development | N/A — adjusted in-camera |
| **Latitude** | Negative film: 2-3 stops overexposure tolerance | Limited highlight recovery |

### Push and Pull Processing

Unlike digital, film photographers can intentionally rate film at a different ISO and compensate during development:

- **Push processing**: Rate ISO 400 film at ISO 800 or 1600, then extend development time. Increases contrast and grain.
- **Pull processing**: Rate ISO 400 film at ISO 200, then reduce development time. Decreases contrast.

<div class="bilingual-content" lang="zh-Hans">
<p><strong>推冲与拉冲</strong>：胶片摄影独有的技术。推冲（push）= 按更高 ISO 拍摄，延长冲洗时间；拉冲（pull）= 按更低 ISO 拍摄，缩短冲洗时间。推冲增加对比度和颗粒，拉冲则相反。</p>
</div>

---

## Stop Increments / 档位增量

FilmMeter supports three step sizes for precise exposure control:

| Step Size | Aperture Example | Shutter Example |
|---|---|---|
| **Full stop** | f/2.8 → f/4 | 1/125 → 1/250 |
| **1/2 stop** | f/2.8 → f/3.5 → f/4 | 1/125 → 1/180 → 1/250 |
| **1/3 stop** | f/2.8 → f/3.2 → f/3.5 → f/4 | 1/125 → 1/160 → 1/200 → 1/250 |

Most modern cameras use 1/3-stop increments. Older manual cameras typically use full stops or half stops.

<div class="bilingual-content" lang="zh-Hans">
<p>FilmMeter 支持三种步进精度：<strong>整档</strong>、<strong>半档</strong>、<strong>1/3 档</strong>。现代相机多用 1/3 档，老式手动相机通常为整档或半档。选择与你的相机匹配的步进精度可以获得最精确的曝光设置。</p>
</div>

---

## Exposure Compensation / 曝光补偿

Sometimes the meter reading needs adjustment based on the scene:

| Scene | Compensation | Reason |
|---|---|---|
| Snow / white sand | +1 to +2 EV | Meter wants to underexpose white |
| Black subject | -1 to -2 EV | Meter wants to overexpose dark |
| Backlit subject | +1 to +2 EV | Background is much brighter |
| Stage lighting | -1 EV | High contrast, preserve highlights |

FilmMeter's [AI Scene Detection]({{ '/features/scene-detection/' | relative_url }}) handles this automatically by recognizing scene types and applying appropriate compensation.

<div class="bilingual-content" lang="zh-Hans">
<p>测光表总是试图将场景还原为中灰（18% 灰）。雪景、白沙需要增加曝光（+1~2 EV），深色主体需要减少曝光（-1~2 EV）。FilmMeter 的 AI 场景识别可以自动处理这些补偿。</p>
</div>

---

## Practicing with FilmMeter / 用 FilmMeter 实践

FilmMeter is the ideal tool for learning and applying the exposure triangle:

1. **Real-time metering** — See how aperture, shutter speed, and ISO interact as you adjust each setting
2. **Step size control** — Switch between 1/3, 1/2, and full stop increments to match your camera
3. **Scene detection** — AI automatically suggests exposure compensation for tricky scenes
4. **Depth of field preview** — See the DOF impact of your aperture choice with our [DOF calculator]({{ '/features/depth-of-field/' | relative_url }})
5. **Film stock selection** — Choose from 21 film stocks and see how ISO affects your available settings

{% include app-cta.html %}

---

## Related Content

<div class="related-links-grid">
  <a href="{{ '/features/light-metering/' | relative_url }}" class="related-link">
    <strong>Light Metering</strong>
    <span>Precision exposure measurement</span>
  </a>
  <a href="{{ '/guides/reciprocity/' | relative_url }}" class="related-link">
    <strong>Reciprocity Guide</strong>
    <span>Long exposure compensation</span>
  </a>
  <a href="{{ '/features/scene-detection/' | relative_url }}" class="related-link">
    <strong>AI Scene Detection</strong>
    <span>Automatic exposure compensation</span>
  </a>
  <a href="{{ '/film-stocks/' | relative_url }}" class="related-link">
    <strong>Film Stock Database</strong>
    <span>Browse all 21 film stocks</span>
  </a>
</div>
