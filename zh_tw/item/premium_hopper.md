[← 回主頁](../)
# 高級漏斗
分類機器？不妨試試看這個！

## 資料
<table>
    <tr><td align="end">圖像</td><td><img src="https://i.imgur.com/N3E9xsp.png" width="128"/></td></tr>
    <tr><td align="end">堆疊</td><td>64</td></tr>
    <tr><td align="end">附魔</td><td>無</td></tr>
</table>

---

## 合成
<table>
    <tr><td><img src="https://i.imgur.com/wl43BjZ.png" width="48"/></td><td><img src="https://i.imgur.com/Mlvbp1T.png" width="48"/></td><td><img src="https://i.imgur.com/wl43BjZ.png" width="48"/></td><td colspan="3"></td></tr>
    <tr><td><img src="https://i.imgur.com/wl43BjZ.png" width="48"/></td><td><img src="https://i.imgur.com/arQApB0.png" width="48"/></td><td><img src="https://i.imgur.com/wl43BjZ.png" width="48"/></td><td width="70" align="center"><img src="https://i.imgur.com/VE0KqIE.png" width="40"/></td><td><img src="https://i.imgur.com/N3E9xsp.png" width="48"/></td><td width="70"></td></tr>
    <tr><td><img src="https://i.imgur.com/wl43BjZ.png" width="48"/></td><td><img src="https://i.imgur.com/PMNWDP6.png" width="48"/></td><td><img src="https://i.imgur.com/wl43BjZ.png" width="48"/></td><td colspan="3"></td></tr>
</table>
※材料包含投擲器

---

## 使用
物品轉送無法轉彎因此只能從上到下，容器可以是：
- 儲物箱
- 陷阱儲物箱
- 木桶
- 界伏盒
- 發射器
- 投擲器
- 漏斗

高級漏斗放置後右鍵開啟選單，

<table>
    <tr><td align="center">標題</td><td colspan="9">高級漏斗</td></tr>
    <tr><td align="center">選擇要分類的物品、選單<br/>9 x 1</td><td><img src="https://i.imgur.com/wl43BjZ.png" width="48"/></td><td><img src="https://i.imgur.com/wl43BjZ.png" width="48"/></td><td><img src="https://i.imgur.com/wl43BjZ.png" width="48"/></td><td><img src="https://i.imgur.com/wl43BjZ.png" width="48"/></td><td><img src="https://i.imgur.com/7ajRlAF.png" width="48"/></td><td><img src="https://i.imgur.com/wl43BjZ.png" width="48"/></td><td><img src="https://i.imgur.com/wl43BjZ.png" width="48"/></td><td><img src="https://i.imgur.com/wl43BjZ.png" width="48"/></td><td><img src="https://i.imgur.com/sAwvuIi.png" width="48"/></td></tr>
</table>

<table>
    <tr><td align="center"><img src="https://i.imgur.com/7ajRlAF.png" width="48"/></td><td>選擇要分類的物品</td></tr>
    <tr><td align="center"><img src="https://i.imgur.com/sAwvuIi.png" width="48"/></td><td>關閉</td></tr>
</table>

### 指定數量
不指定數量的情況下，每次移動都會採取最大值數量。
<table>
    <tr><td>在<a href="https://minecraft.fandom.com/zh/wiki/鐵砧">鐵砧</a>改成想要的數量</td><td><img src="https://i.imgur.com/XczBIwu.png" width="720"/></td></tr>
    <tr><td>放置</td><td><img src="https://i.imgur.com/AJJzsmO.png" width="720"/></td></tr>
</table>

### 被動模式
在沒有紅石信號時，將上方的掉落物往下移動，  

<img src="https://i.imgur.com/GrdXkPA.png" width="720"/>

<table>
    <tr><td align="center">指定數量</td><td align="center">行為</td></tr>
    <tr><td align="center">有指定</td><td align="center">每次移動固定掉落物數量</td></tr>
    <tr><td align="center">沒有指定</td><td align="center">每次移動最大掉落物數量</td></tr>
</table>

每次移動成功都會觸發方塊更新，可使用偵測器監聽並觸發紅石信號，

<img src="https://i.imgur.com/HqB0NR7.png" width="720"/>

下方容器無法放入更多物品會變為掉落物。  


### 主動模式
每次觸發紅石信號時，將上方的內容物往下移動，  

<img src="https://i.imgur.com/74aYGNN.png" width="720"/>
<table>
    <tr><td align="center">指定數量</td><td align="center">行為</td></tr>
    <tr><td align="center">有指定</td><td align="center">每次移動固定內容物數量</td></tr>
    <tr><td align="center">沒有指定</td><td align="center">每次移動最大內容物數量</td></tr>
</table>

下方容器無法放入更多物品會變為掉落物。
