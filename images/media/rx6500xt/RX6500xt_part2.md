---
title: "[開箱]  ASUS TUF Gaming RX 6500 XT  安裝在B350只有PCIe 3.0底板還可以流暢玩遊戲嗎?Part 2"
date: 2022-01-30T01:29:33+08:00
draft: false


---
3DMark跑分&遊戲benchmark
---
測試平台  
CPU: AMD R7 1700  
MB: ASRock AB350 Pro4  
RAM: Galax HOF 3200c14 8GB x2  
SSD: Plextor m9p+ 1TB  
PSU: Seasonic PRIME Ultra Titanium 650W  
CASE: Silverstone FT02   
OS: WIN 10 pro 21H1

R7 360 fire strike跑分  
![firestrike_r7360](media/firestrike_r7360.png)

RX 6500 XT fire strike跑分  
![firestrike_6500](media/firestrike_6500-1.JPG)

R7 360 time spy分  
![timespy_r7360](media/timespy_r7360-1.png)

RX 6500 XT time spy跑分  
![timespy_r7360](media/timespy_r7360.png)


舊卡R7 360遊戲只測試了dota2，因為玩其他遊戲像看幻燈片一樣，要完整玩完一埸都十分困難。而且AMD也於21年7月停止更新driver，部份遊戲如 Battlefield 2042 會提示顯示卡驅動程式太舊 無法運行遊戲。  

Dota2 以vulkan 執行fps比較不穩定 上下限差異大，R7 360在vulkan下最低只有0.7 fps, 每當團戰時會嚴重掉幀，整個畫面像凍結一樣，團戰後才開始回復，往往成為千古罪人  
RX 6500 XT  以dx11 執行 最高fps是4次測試中最低的70幀，最低fps卻是最高的接近60幀  
![dota2](media/dota2.png)

Forza Horizon 5 High 畫質也有平均56fps，十分流暢 。High畫質下由於vram不足，fps大幅下降  
![fh5](media/fh5.png)

Halo Infinite, CS:GO, Civilization 6, Back4blood 這4款中只有Halo Infinite開Low畫質都跑不順，僅有39fps
![games](media/games.png)

FurMark和閒置時溫度功耗比較  
燒機溫度可保持在60 °C內，功耗約90W; 而閒置功耗只有約2W，相信將來推出的RDNA2架構效能功耗比會不錯  
![temp](media/temp.png)



 
 
 
 
 
 
 


總結
---
AMD首款RDNA2 使用6nm 製程的卓面顯示卡，卻它把閹割得太過份，把不少應有的規格功能都大刀去掉，這樣做唯一好處是礦工都不會使用這卡，卻苦了一般的用家。

雖RX 6500 XT  就算在PCIe 3.0 X4下還是大都可以跑到平均60FPS，不過只有4 GB VRAM實在太吃緊，很多3A大作中畫質下已經佔用超過3GB了，日後推出的3A大作可能會超過4GB，令中低畫質下也跑不滿60FPS。AMD 自己也曾出文說4GB 滿足不了現今遊戲需求，不過已於不久前刪文，此舉耐人尋味；
而且也不支援影像編碼和AV1解碼，日後淘汰把想它安裝往HTPC/NAS當作影片解碼轉檔卡也不太勝任。只能算是騎牛搵馬的選擇，捱到顯示卡價回復正常再入手正常的卡。

>套用食神的對白  
>***啲 VRAM有咁少得咁少，PCIe LANE有咁窄得咁窄， 啲 vram chur一聲用完咪等d友用得咁舒服，用過拿拿聲買過第二張囉！***


如有下列的條件還是可入手啦！  
+ 預算十分不足  
+ 1080 中/低畫質就滿足  



不過如有下列要求就不建議入手了  
- 串流直播 影片轉檔剪輯(除非有iGPU可使用)  
- 打算長期使用2至3年不換卡  
- 可接受購買二手卡  