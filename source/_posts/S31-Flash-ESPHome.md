---
title: S31 Flash ESPHome
date: 2023-07-13 10:12:05
tags:
  - ESPHome
  - IoT
  - Home Assistant
---

在智能家居領域，我們常採用 [Sonoff S31](https://sonoff.tech/product/smart-plugs/s31-s31lite/) 作為智能開關，它能夠讓您更加靈活地控制家中的電器和設備。
然而，我們會選擇對其進行刷機，以獲得更多的功能和控制權，最主要是與 Home Assistant 進行連接。

在刷機上會有兩大陣營，分別是走 MQTT 的 [Tasmota](https://tasmota.github.io/docs/) 與 API 的 [ESPHome](https://esphome.io/index.html)

## Tasmota 與 ESPHome 的差別
基本上在泛用性上 ESPHome 是最佳解
{% img "w:500 ml:8!" /images/posts/2023-07-13_224957.png %}

## 拆解
  1. 拆開蓋板
  2. 抽出兩個邊條
  3. 取下螺絲
  4. 取出主板

{% youtube IvfiLcHMekQ %}





## 參考資料

- [NT$200，sonoff s31 測電量插座刷機經驗分享(ESPHome) - 創客分享 - Automata](https://forum.automata.id/t/topic/221)
- [esphome、tasmota、的优缺 [欢迎讨论] - 『HomeAssistant』求助&解答专区 - 『瀚思彼岸』» 智能家居技术论坛 - Powered by Discuz! (hassbian.com)](https://bbs.hassbian.com/thread-8812-1-1.html)
- [ESPHome vs Tasmota (And How To Switch Between Them) – Siytek](https://siytek.com/esphome-vs-tasmota/)
