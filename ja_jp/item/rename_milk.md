# 改名牛奶
這裡不是戶政事務所，別改上癮，因為會導致沒人認識你...

## 資料
<table>
    <tr><td align="end">圖像</td><td><img src="https://i.imgur.com/YX4uOZG.png" width="128"/></td></tr>
    <tr><td align="end">堆疊</td><td>1</td></tr>
    <tr><td align="end">附魔</td><td>無</td></tr>
</table>

---

## 合成
<table>
    <tr><td><img src="https://i.imgur.com/Nz7hGwj.png" width="48"/></td><td><img src="https://i.imgur.com/Ld5I67V.png" width="48"/></td><td><img src="https://i.imgur.com/Nz7hGwj.png" width="48"/></td><td colspan="3"></td></tr>
    <tr><td><img src="https://i.imgur.com/Nz7hGwj.png" width="48"/></td><td><img src="https://i.imgur.com/Tg2ncsJ.png" width="48"/></td><td><img src="https://i.imgur.com/Nz7hGwj.png" width="48"/></td><td width="70" align="center"><img src="https://i.imgur.com/VE0KqIE.png" width="40"/></td><td><img src="https://i.imgur.com/YX4uOZG.png" width="48"/></td><td width="70"></td></tr>
    <tr><td><img src="https://i.imgur.com/Nz7hGwj.png" width="48"/></td><td><img src="https://i.imgur.com/Nz7hGwj.png" width="48"/></td><td><img src="https://i.imgur.com/Nz7hGwj.png" width="48"/></td><td colspan="3"></td></tr>
</table>

---

## 使用
<table>
    <tr><td>更改前</td><td><img src="https://i.imgur.com/OfuTr8T.png" width="720"/></td></tr>
    <tr><td>在<a href="https://minecraft.fandom.com/zh/wiki/鐵砧">鐵砧</a>改成想要的暱稱</td><td><img src="https://i.imgur.com/kaBHSxn.png" width="720"/></td></tr>
    <tr><td>喝下去</td><td><img src="https://i.imgur.com/QfU8njF.png" width="720"/><br/>改名牛奶將被消耗。</td></tr>
</table>
如果暱稱已被占用導致不可更改，會返還消耗的改名牛奶。

---

## 顯示
在任何地方都優先顯示暱稱，暱稱與ID一樣則只會顯示ID：
<table>
    <tr><td align="center">手機認證</td><td align="center">暱稱與ID一樣</td><td align="center">暱稱與ID不一樣</td></tr>
    <tr><td align="center">沒有</td><td align="center">xuancat0208</td><td align="center">旋(xuancat0208)</td></tr>
    <tr><td align="center">有</td><td align="center">xuancat0208✓</td><td align="center">旋(xuancat0208)✓</td></tr>
</table>

區分大小寫，可輸入最多16個字元，特定字元將會被轉換成 `_`*(底線)*：
<table>
    <tr><td align="center">字元</td><td align="center">名稱</td><td align="center">統一碼</td></tr>
    <tr><td align="center">&ensp;</td><td align="center">半型空格</td><td align="center">u+0020</td></tr>
    <tr><td align="center">&emsp;</td><td align="center">全型空格</td><td align="center">u+3000</td></tr>
    <tr><td align="center">=</td><td align="center">等於</td><td align="center">u+003d</td></tr>
    <tr><td align="center">#</td><td align="center">井字</td><td align="center">u+0023</td></tr>
    <tr><td align="center">@</td><td align="center">At</td><td align="center">u+0040</td></tr>
    <tr><td align="center">(</td><td align="center">括號開始</td><td align="center">u+0028</td></tr>
    <tr><td align="center">)</td><td align="center">括號結束</td><td align="center">u+0029</td></tr>
    <tr><td align="center">`</td><td align="center">重音符</td><td align="center">u+0060</td></tr>
    <tr><td align="center">!</td><td align="center">驚嘆</td><td align="center">u+0021</td></tr>
    <tr><td align="center">/</td><td align="center">斜線</td><td align="center">u+002f</td></tr>
    <tr><td align="center">\</td><td align="center">反斜線</td><td align="center">u+005c</td></tr>
    <tr><td align="center">✓</td><td align="center">打勾</td><td align="center">u+2713</td></tr>
</table>

例如 `I=M~C@M e` 變為 `I_M~C_M_e`。 

全伺服器相同暱稱只能有一個：

<table>
    <tr><td align="center">已被ID使用</td><td align="center">已被暱稱使用</td><td align="center">可以更改</td></tr>
    <tr><td align="center" rowspan="2">沒有</td><td align="center">有</td><td align="center">拒絕</td></tr>
    <tr><td align="center">沒有</td><td align="center">允許</td></tr>
    <tr><td align="center" colspan="2">自己</td><td align="center">允許</td></tr>
    <tr><td align="center" rowspan="2">有</td><td align="center">有</td><td align="center">拒絕</td></tr>
    <tr><td align="center">沒有</td><td align="center">拒絕</td></tr>
</table>