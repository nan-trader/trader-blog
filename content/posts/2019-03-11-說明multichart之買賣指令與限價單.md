---
title: 說明Multichart之買賣指令與限價單
date: 2019-03-10T16:17:26.498Z
description: 說明Multichart之買賣指令與限價單
thumbnail: /img/uploads/rawpixel-788601-unsplash.jpg
tags:
  - Multichart
categories:
  - 程式交易語法
---
商品不是只有買跟賣嗎？

怎麼有四種買賣指令？掛出去的限價單還有兩種？！一共八種組合...

初學者常常在這裡搞不懂，尤其又加上程式混雜者各種交易邏輯，情況又更複雜了

<-!more->

聽Nan來慢慢說明

Multichart一共有四個交易指令：

* Buy - 多單進場
* Sell - 多單出場
* SellShort - 空單進場
* BuytoCover - 空單出場

先撇開交易邏輯的部分，當好不容易等到訊號出現，要進行買賣的時候，依照訊號看多或是看空下



第一件事情要判斷"手上部位"。是**空手**還是有**多、空部位**？

如果是**空手**，那只能下進場指令，也就是Buy(看多)或是SellShort(看空)

如果是手上有**多單**，那只能下Buy或是Sell

反之如果手上有**空單**，那就只能下SellShort或是BuytoCover

下到不允許的指令，不會執行喔！
