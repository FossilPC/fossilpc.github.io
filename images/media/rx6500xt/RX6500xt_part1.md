---
title: "[開箱]  ASUS TUF Gaming RX 6500 XT  安裝在B350只有PCIe 3.0底板還可以流暢玩遊戲嗎?Part 1"
date: 2022-01-30T01:29:33+08:00
draft: false


---
前文
---
晶片短缺，掘礦熱潮，黃牛炒賣等因素影響下，顯示卡價
格已居高不下多時，要入手顯示卡實在頭痛！

極不幸地 Sapphire R7 360 幾個月前開機經常沒有畫面，近來越發頻繁，無何奈何只好入手一張新的。因預算不足又不想買到二手礦卡，所以選擇了於1月新發佈的ASUS TUF Gaming RX 6500 XT。時隔6年的升級，用在只有PCIe 3.0的B350底板上到底會帶來多少提升? 

開箱
---

![](qownnotes-media-zlampb.png)

TUF Gaming RX 6500 XT OC 4GB 包裝正面，印有一些卡的基本資料， 適合1080p遊戲, 4GB GDDR6 VRAM, 對應 AURA SYNC, PCIe 4.0  
!{{ $image := .Resources.GetMatch "qownnotes-media-zlampb.png" }})

包裝背面，印有更詳細的資料  
![qownnotes-media-PeOTGg](media/qownnotes-media-PeOTGg.png)

內紙盒，除了燙金ASUS字樣外還有ASUS的紋理  
![qownnotes-media-wuzvua](media/qownnotes-media-wuzvua.png)

打開紙盒，首先看見一樣印有燙金ASUS的紙卡套  
![qownnotes-media-uuyumc](media/qownnotes-media-uuyumc.png)

紙卡套裹放有感謝卡，說明書和保養卡  
![qownnotes-media-zgxiDs](media/qownnotes-media-zgxiDs.png)

再下層就是防靜電袋包覆的顯示卡  
![qownnotes-media-CyKUce](media/qownnotes-media-CyKUce.png)
![qownnotes-media-YRYlmy](media/qownnotes-media-YRYlmy.png)

拆袋就是本文的主⻆ ASUS TUF Gaming RX 6500 XT 
雙風扇, 金屬前背板, 背板有拉絲表面處理 看上去更高貴  
![qownnotes-media-KKGTgV](media/qownnotes-media-KKGTgV.png)
![qownnotes-media-OxgokY](media/qownnotes-media-OxgokY.png)

正上方可看到 6PIN供電按口, RGB燈設在TUF Logo和斜面上的小直條
![qownnotes-media-MBaywN](media/qownnotes-media-MBaywN.png)

雙 9.5cm 軸向式風扇, 扇葉和外圍圓環相連, 加強氣流輔助散熱  
低負載時保持靜止，減低噪音。當溫度高於57°C開轉動，并於溫度降至50°C才停轉，避免風扇頻煩重啟
![qownnotes-media-wRmsrr](media/qownnotes-media-wRmsrr.png)

4導熱管和大面積散熱鰭片，用在功耗和發熱都不高的 6500 XT 實在是殺雞用牛刀！顯示卡在高負載下也能保持十分低溫  
![qownnotes-media-tpxsJF](media/qownnotes-media-tpxsJF.png)

雖然擁有x16金手指，不過實際上只有x4的通道有接通  
![qownnotes-media-jFdXlt](media/qownnotes-media-jFdXlt.png)

輸出port為HDMI 2.1和 DisplayPort 1.4a 各一  
只能接駁兩台螢幕  
![qownnotes-media-DGuMJS](media/qownnotes-media-DGuMJS.png)

新舊卡合照  
![qownnotes-media-VFNQpH](media/qownnotes-media-VFNQpH.png)

上機! 由於卡有2.7 slot厚, 所以主板的第三Slot的PCIe x4槽會被阻檔  
![qownnotes-media-CpuiYW](media/qownnotes-media-CpuiYW.png)

不插上電源的話傍邊的led會亮起  
![DSCF1304](media/DSCF1304.jpg)

開機  全機唯一RGB設備，之後應該也會關掉RGB  
![qownnotes-media-PlFIaY](media/qownnotes-media-PlFIaY.png)


規格
---
 GPU-Z 左為RX 6500 XT ，右為R7 360  
![2](media/2-1.gif)

這卡最尷尬的是**PCIe 4.0 x4**，如果像本文一樣用在只有PCIe 3.0的主板，也只能跑**PCIe 3.0 x4** ，令效能下降。
>|  PCIe 版本|x4 頻寬  |
>|---|---|
>| 3.0 | 3.94 GB/s |
>| 4.0 | 7.88 GB/s 	 |

支援 H254, HEVC(H265), VP9解碼，至於明日新星 AV1就欠缺了  
另外要特別注意的是**不支援任何編碼**!  
![dxva_decode](media/dxva_decode.JPG)









