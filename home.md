---
title: База знаний
description: Сводная страница разделов WIKI
published: true
date: 2025-04-11T15:13:18.788Z
tags: 
editor: markdown
dateCreated: 2025-03-30T12:15:39.169Z
---

# Руководства

---

<style>
  .hover-zoom {
    transition: transform 0.3s ease;
  }

  .hover-zoom:hover {
    transform: scale(1.08);
  }

  .tooltip-container {
    position: relative;
    display: inline-block;
  }

  .tooltip-text {
    visibility: hidden;
    width: max-content;
    max-width: 200px;
    background-color: #007BFF;
    color: #fff;
    text-align: center;
    border-radius: 10px;
    border: 2px solid #000;
    padding: 8px 12px;
    position: absolute;
    z-index: 1;
    top: 110%; /* Появляется СНИЗУ */
    left: 50%;
    transform: translateX(-50%);
    font-family: 'Comic Sans MS', cursive, sans-serif;
    font-size: 14px;
    box-shadow: 3px 3px 0 #000;
    opacity: 0;
    transition: opacity 0.3s;
  }

  .tooltip-container:hover .tooltip-text {
    visibility: visible;
    opacity: 1;
  }

  .tooltip-text::after {
    content: "";
    position: absolute;
    bottom: 100%; /* Стрелка сверху у подсказки */
    left: 50%;
    margin-left: -6px;
    border-width: 6px;
    border-style: solid;
    border-color: transparent transparent #000 transparent;
  }
</style>

<div style="display: flex; gap: 16px; flex-wrap: wrap; align-items: left; justify-content: left;">

  <div style="text-align: center;">
    <a href="/home/styleguide" target="_blank" class="tooltip-container">
      <img 
        src="/u6639615556_draw_a_funny_cover_for_the_book_technical_documen_3b94d54b-760a-4b54-bc69-f76d418592dc_2.png"
        class="hover-zoom"
        style="border-radius: 25px; animation: pulse 1.5s infinite; width: 200px; height: auto;">
      <div class="tooltip-text">СТИЛЬ ИЗЛОЖЕНИЯ</div>
    </a>
  </div>

  <div style="text-align: center;">
    <a href="/home/Markdown" target="_blank" class="tooltip-container">
      <img 
        src="/u6639615556_ill_draw_a_funny_picture_of_two_people_arguing_ab_5f6a47e7-c821-425e-80e1-f0456353a5dc_0.png"
        class="hover-zoom"
        style="border-radius: 25px; animation: pulse 1.5s infinite; width: 200px; height: auto;">
      <div class="tooltip-text">РАЗМЕТКА</div>
    </a>
  </div>
  
</div>