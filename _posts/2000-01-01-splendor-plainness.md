---
layout: post
title: The shader of splendor plainness
author: "CMH"
categories: techart
tags: [techart]
image: BlackPaysage_01.png
---

「璀璨至極的淡」技法論述，以歧異的風景-鬱金為例：  
1. 以Perlin noise結合fBm，建構雲的三維模型，產生第一代雲。
2. 以raymarching結合volumetric clouds rendering，藉此表現三維雲模型之立體光影表現。參考文獻有Inigo Quilez's directional derivative(2013) & better fog(2010)。
4. 受Inigo Quilez's domain warping(2002)啟發，由第一代雲演化生成第二代雲，再演化生成第三代雲。每一代雲的變異皆導致更為詭異特徵，與其說是雲的模型，更接近細碎柳絮，又或是混沌狀態的氣。
5. 受杉本博司海景系列啟發，透過時間作用，不斷累積即時瞬間的第三代變異量體雲，聚集成具有古典氣質之光影雲彩感。
6. 換言之，第三步透過演化變異追求璀璨至極，第四步驟則是回歸於淡。




[About the Lab]({{ site.github.url }}{% post_url 2021-09-23-welcome-to-lab %}).
[About the Author]({{ site.github.url }}{% post_url 2021-09-24-about-the-author %}).
