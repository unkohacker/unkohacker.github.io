---
title: "null"
permalink: "null/"
layout: "null"
---

# 自己紹介

やあ

## 肩書き

現在、物理M2。  
来年、底辺SIer。

## 好きなたべもの

- ステーキ
- のり弁

## 趣味

いろいろ

## おすすめ

{% assign youtube_ids = "
  q7SbeF3Oqu8
  Ksf_gq6fZZM
  6bnaBnd4kyU
  65MVxnJbS0c
  4_fvGiulqk8
  lGXgYHlR8ww
  TnQgSAaGhVc
  o1e9hdMjUi0
  zixZ0THZO8w
  eTEVPS3p6k0
" | split: " " %}

<div class="youtube-grid">
{%- for youtube_id in youtube_ids %}
  {%- include youtube.html id = youtube_id -%}
{%- endfor %}
</div>

