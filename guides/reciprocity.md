---
layout: feature
title: "Reciprocity Failure Guide - Long Exposure Compensation for Film Photography"
description: "Complete guide to reciprocity failure compensation. Lookup tables and formulas for 21 film stocks. 倒易率失效指南：胶片长曝光补偿公式与数据表。"
permalink: /guides/reciprocity/
---

<nav class="breadcrumb">
  <a href="{{ '/' | relative_url }}">Home</a>
  <span>/</span>
  <a href="{{ '/guides/' | relative_url }}">Guides</a>
  <span>/</span>
  <span>Reciprocity Failure</span>
</nav>

<div class="feature-page-hero">
  <h1>Reciprocity Failure Guide</h1>
  <p class="zh-subtitle" lang="zh-Hans">倒易率失效 — 胶片长曝光补偿完全指南</p>
  <p>When film exposures exceed approximately 1 second, the relationship between light intensity and exposure time becomes non-linear. This phenomenon is called <strong>reciprocity failure</strong> (or reciprocity law failure), and it requires exposure compensation to achieve correct density on film.</p>
</div>

## What is Reciprocity Failure? / 什么是倒易率失效？

The **reciprocity law** states that exposure = intensity × time. For most photography, doubling the time at half the intensity produces the same result. However, at very long or very short exposure times, film emulsion becomes less sensitive — this is **reciprocity failure**.

<div class="bilingual-content" lang="zh-Hans">
<p><strong>倒易率</strong>（互易律）指的是曝光量 = 光强 × 时间。在大多数情况下，将时间加倍、光强减半可以得到相同的曝光效果。但在极长或极短曝光时间下，胶片乳剂的感光效率会降低——这就是<strong>倒易率失效</strong>。</p>
</div>

### Why It Matters for Film Photographers

- **Night photography**: Exposures of 10 seconds or more require significant compensation
- **Long exposure landscapes**: Waterfalls, cloud streaks, star trails
- **Low-light interiors**: Architectural and interior photography
- **ND filter use**: When neutral density filters push exposure times beyond 1 second

---

## Compensation Methods / 补偿方法

### Method 1: Power Formula (Tc = Tm^P)

The most common mathematical approach uses a power factor **P** specific to each film stock:

**Corrected Time = (Metered Time) ^ P**

Where:
- **Tc** = corrected exposure time (seconds)
- **Tm** = metered exposure time (seconds)
- **P** = reciprocity factor (film-specific, typically 1.1 to 1.5)

**Example**: If your meter reads 4 seconds with Kodak Portra 400 (P ≈ 1.3):
- Tc = 4^1.3 ≈ 6.1 seconds

<div class="bilingual-content" lang="zh-Hans">
<p><strong>公式法</strong>：校正时间 = 测量时间^P。其中 P 是每种胶片特有的倒易率系数，通常在 1.1 到 1.5 之间。P 值越大，该胶片在长曝光时需要的补偿越多。</p>
</div>

### Method 2: Lookup Tables

Some manufacturers provide specific lookup tables mapping metered time to corrected time. This is more accurate than the formula method when official data is available.

| Metered Time | Example Correction (P=1.3) |
|---|---|
| 1s | 1.0s |
| 2s | 2.5s |
| 4s | 6.1s |
| 8s | 15.0s |
| 15s | 33.6s |
| 30s | 82.4s (≈ 1m 22s) |
| 60s | 202s (≈ 3m 22s) |
| 120s | 496s (≈ 8m 16s) |

---

## Film Stock Reciprocity Data Summary / 各胶卷倒易率数据

The table below summarizes reciprocity characteristics for all 21 film stocks in the FilmMeter database. Click each film name for detailed specifications.

### Color Negative Films / 彩色负片

| Film Stock | ISO | P Factor | Threshold | Data Source |
|---|---|---|---|---|
| [Kodak Portra 400]({{ '/film-stocks/kodak-portra-400/' | relative_url }}) | 400 | 1.30 | 1s | Kodak Technical Pub |
| [Kodak Portra 160]({{ '/film-stocks/kodak-portra-160/' | relative_url }}) | 160 | 1.30 | 1s | Kodak Technical Pub |
| [Kodak Portra 800]({{ '/film-stocks/kodak-portra-800/' | relative_url }}) | 800 | 1.30 | 1s | Kodak Technical Pub |
| [Kodak Gold 200]({{ '/film-stocks/kodak-gold-200/' | relative_url }}) | 200 | 1.30 | 1s | Kodak Technical Pub |
| [Kodak ColorPlus 200]({{ '/film-stocks/kodak-colorplus-200/' | relative_url }}) | 200 | 1.30 | 1s | Estimated |
| [Kodak UltraMax 400]({{ '/film-stocks/kodak-ultramax-400/' | relative_url }}) | 400 | 1.30 | 1s | Estimated |
| [Kodak Ektar 100]({{ '/film-stocks/kodak-ektar-100/' | relative_url }}) | 100 | 1.30 | 1s | Kodak Technical Pub |
| [Fujifilm Superia 400]({{ '/film-stocks/fujifilm-superia-400/' | relative_url }}) | 400 | 1.30 | 1s | Estimated |
| [CineStill 800T]({{ '/film-stocks/cinestill-800t/' | relative_url }}) | 800 | 1.30 | 1s | Community tested |
| [Harman Phoenix 200]({{ '/film-stocks/harman-phoenix-200/' | relative_url }}) | 200 | 1.35 | 1s | Estimated |
| [LeKai C200]({{ '/film-stocks/lekai-c200/' | relative_url }}) | 200 | 1.30 | 1s | Estimated |
| [Kodak 5207 250D]({{ '/film-stocks/kodak-5207-250d/' | relative_url }}) | 250 | 1.30 | 1s | Kodak Technical Pub |
| [Kodak 5219 500T]({{ '/film-stocks/kodak-5219-500t/' | relative_url }}) | 500 | 1.30 | 1s | Kodak Technical Pub |

### Black & White Films / 黑白胶片

| Film Stock | ISO | P Factor | Threshold | Data Source |
|---|---|---|---|---|
| [Ilford HP5 Plus]({{ '/film-stocks/ilford-hp5-plus/' | relative_url }}) | 400 | 1.31 | 1s | Ilford Official |
| [Ilford Delta 400]({{ '/film-stocks/ilford-delta-400/' | relative_url }}) | 400 | 1.41 | 1s | Ilford Official |
| [Ilford Delta 100]({{ '/film-stocks/ilford-delta-100/' | relative_url }}) | 100 | 1.26 | 1s | Ilford Official |

### Reversal / Slide Films / 反转片

| Film Stock | ISO | P Factor | Threshold | Data Source |
|---|---|---|---|---|
| [Fujifilm Velvia 50]({{ '/film-stocks/fujifilm-velvia-50/' | relative_url }}) | 50 | 1.30 | 1s | Fujifilm Technical |
| [Fujifilm Velvia 100F]({{ '/film-stocks/fujifilm-velvia-100f/' | relative_url }}) | 100 | 1.30 | 4s | Fujifilm Technical |
| [Fujifilm Provia 100F]({{ '/film-stocks/fujifilm-provia-100f/' | relative_url }}) | 100 | 1.30 | 1s | Fujifilm Technical |
| [Kodak Ektachrome E100]({{ '/film-stocks/kodak-ektachrome-e100/' | relative_url }}) | 100 | 1.30 | 1s | Kodak Technical Pub |
| [Kodak 5294 100D]({{ '/film-stocks/kodak-5294-100d/' | relative_url }}) | 100 | 1.30 | 1s | Estimated |

---

## Film Type Differences / 不同胶片类型的差异

### Black & White
B&W films generally have well-documented reciprocity data. Ilford provides official reciprocity correction factors for all their films. B&W films are also more forgiving due to wider exposure latitude.

### Color Negative
Modern color negative films like Kodak Portra have relatively mild reciprocity failure. Kodak publishes some data in technical publications, but many consumer films rely on community-tested estimates.

### Reversal / Slide Film
Slide films have the narrowest exposure latitude, making accurate reciprocity compensation critical. Slight underexposure from uncorrected reciprocity failure can result in noticeably dark slides.

<div class="bilingual-content" lang="zh-Hans">
<p><strong>黑白片</strong>通常有最完整的官方数据，且宽容度高，容错空间大。<strong>彩色负片</strong>现代产品倒易率失效较轻。<strong>反转片</strong>宽容度最窄，倒易率补偿的准确性至关重要。</p>
</div>

---

## Practical Tips / 实用技巧

1. **Start compensating at 1 second** — Most films begin showing reciprocity failure around 1s exposure time
2. **Bracket your exposures** — When in doubt, shoot one frame at calculated compensation and one at +1 stop
3. **Consider color shifts** — Long exposures on color film can cause color shifts; this is more pronounced on slide film
4. **Use FilmMeter's auto compensation** — The app automatically calculates corrected exposure times based on your selected film stock

<div class="bilingual-content" lang="zh-Hans">
<h3>实用建议</h3>
<ol>
<li><strong>1秒以上开始补偿</strong> — 大多数胶片在1秒以上开始出现明显的倒易率失效</li>
<li><strong>包围曝光</strong> — 不确定时，按计算值拍一张，再多加一档拍一张</li>
<li><strong>注意色偏</strong> — 彩色胶片长曝光会产生色偏，反转片更为明显</li>
<li><strong>使用 FilmMeter 自动补偿</strong> — App 会根据所选胶卷自动计算校正后的曝光时间</li>
</ol>
</div>

---

## Automatic Compensation with FilmMeter / 使用 FilmMeter 自动补偿

FilmMeter includes built-in reciprocity failure compensation for all 21 film stocks. When your metered exposure exceeds the threshold (typically 1 second), the app automatically:

1. Detects that the exposure requires compensation
2. Applies the film-specific P factor or lookup table
3. Displays both the metered and corrected exposure times
4. Lets you choose your preferred correction method

{% include app-cta.html %}

---

## Related Content

<div class="related-links-grid">
  <a href="{{ '/features/light-metering/' | relative_url }}" class="related-link">
    <strong>Light Metering</strong>
    <span>Precision exposure measurement</span>
  </a>
  <a href="{{ '/guides/exposure-triangle/' | relative_url }}" class="related-link">
    <strong>Exposure Triangle Guide</strong>
    <span>Aperture, shutter speed & ISO</span>
  </a>
  <a href="{{ '/film-stocks/' | relative_url }}" class="related-link">
    <strong>Film Stock Database</strong>
    <span>Browse all 21 film stocks</span>
  </a>
</div>
