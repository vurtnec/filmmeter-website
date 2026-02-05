---
layout: page
title: "Film Stock Database - 21 Film Stocks with Specs & Reciprocity Data"
description: "Complete film stock database with specifications, reciprocity failure data, and shooting characteristics for 21 popular film stocks. 胶片数据库：21款胶卷参数与倒易率数据。"
permalink: /film-stocks/
---

<div class="feature-page-hero">
  <h1>Film Stock Database</h1>
  <p class="zh-subtitle" lang="zh-Hans">胶片数据库 — 21 款胶卷完整参数与特性</p>
  <p>Comprehensive database of all film stocks included in FilmMeter. Each entry includes ISO, film type, processing chemistry, reciprocity failure data, and shooting characteristics — extracted directly from the app's built-in film library.</p>
</div>

---

## Color Negative Films / 彩色负片 (13)

<div class="film-stocks-grid">

{% for film in site.data.film_stocks %}
  {% if film.film_type == "Color Negative" %}
  <a href="{{ '/film-stocks/' | append: film.slug | append: '/' | relative_url }}" class="film-stock-card">
    <div class="film-stock-card-header" style="background-color: {{ film.brand_color }};">
      <span class="film-type-badge badge-color-negative">Color Negative</span>
    </div>
    <div class="film-stock-card-body">
      <h3>{{ film.full_name }}</h3>
      <div class="film-stock-card-meta">
        <span class="film-iso">ISO {{ film.iso }}</span>
        <span class="film-process">{{ film.process }}</span>
      </div>
      <p class="film-stock-card-desc">{{ film.description_en | truncate: 100 }}</p>
    </div>
  </a>
  {% endif %}
{% endfor %}

</div>

---

## Black & White Films / 黑白胶片 (3)

<div class="film-stocks-grid">

{% for film in site.data.film_stocks %}
  {% if film.film_type == "Black & White" %}
  <a href="{{ '/film-stocks/' | append: film.slug | append: '/' | relative_url }}" class="film-stock-card">
    <div class="film-stock-card-header" style="background-color: {{ film.brand_color }};">
      <span class="film-type-badge badge-bw">B&W</span>
    </div>
    <div class="film-stock-card-body">
      <h3>{{ film.full_name }}</h3>
      <div class="film-stock-card-meta">
        <span class="film-iso">ISO {{ film.iso }}</span>
        <span class="film-process">{{ film.process }}</span>
      </div>
      <p class="film-stock-card-desc">{{ film.description_en | truncate: 100 }}</p>
    </div>
  </a>
  {% endif %}
{% endfor %}

</div>

---

## Reversal / Slide Films / 反转片 (5)

<div class="film-stocks-grid">

{% for film in site.data.film_stocks %}
  {% if film.film_type == "Reversal" or film.film_type == "Reversal (Cinema)" %}
  <a href="{{ '/film-stocks/' | append: film.slug | append: '/' | relative_url }}" class="film-stock-card">
    <div class="film-stock-card-header" style="background-color: {{ film.brand_color }};">
      <span class="film-type-badge badge-reversal">Reversal</span>
    </div>
    <div class="film-stock-card-body">
      <h3>{{ film.full_name }}</h3>
      <div class="film-stock-card-meta">
        <span class="film-iso">ISO {{ film.iso }}</span>
        <span class="film-process">{{ film.process }}</span>
      </div>
      <p class="film-stock-card-desc">{{ film.description_en | truncate: 100 }}</p>
    </div>
  </a>
  {% endif %}
{% endfor %}

</div>

---

## Quick Comparison / 快速对比

| Film Stock | ISO | Type | Process | Reciprocity P Factor |
|---|---|---|---|---|
{% for film in site.data.film_stocks %}| [{{ film.full_name }}]({{ '/film-stocks/' | append: film.slug | append: '/' | relative_url }}) | {{ film.iso }} | {{ film.film_type }} | {{ film.process }} | {{ film.reciprocity_factor }} |
{% endfor %}

---

## Related Resources

<div class="related-links-grid">
  <a href="{{ '/guides/reciprocity/' | relative_url }}" class="related-link">
    <strong>Reciprocity Failure Guide</strong>
    <span>Long exposure compensation formulas and tables</span>
  </a>
  <a href="{{ '/guides/exposure-triangle/' | relative_url }}" class="related-link">
    <strong>Exposure Triangle Guide</strong>
    <span>Aperture, shutter speed & ISO explained</span>
  </a>
  <a href="{{ '/features/light-metering/' | relative_url }}" class="related-link">
    <strong>Light Metering</strong>
    <span>Precision exposure measurement in FilmMeter</span>
  </a>
</div>

{% include app-cta.html %}
