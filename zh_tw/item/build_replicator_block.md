[← 回主頁](../)
# 建築複製器
比藍圖模組方便億點點，也可以看看[建築藍圖](build_blueprint.md)。

## 資料
<table>
    <tr><td align="end">圖像</td><td><img src="https://i.imgur.com/gs5l20b.png" width="128"/></td></tr>
    <tr><td align="end">堆疊</td><td>64</td></tr>
    <tr><td align="end">附魔</td><td>無</td></tr>
</table>

---

## 合成
<table>
    <tr><td><img src="https://i.imgur.com/ip72f4t.png" width="48"/></td><td><img src="https://i.imgur.com/ip72f4t.png" width="48"/></td><td><img src="https://i.imgur.com/ip72f4t.png" width="48"/></td><td colspan="3"></td></tr>
    <tr><td><img src="https://i.imgur.com/ip72f4t.png" width="48"/></td><td><img src="https://i.imgur.com/IWZz8YM.png" width="48"/></td><td><img src="https://i.imgur.com/ip72f4t.png" width="48"/></td><td width="70" align="center"><img src="https://i.imgur.com/VE0KqIE.png" width="40"/></td><td><img src="https://i.imgur.com/gs5l20b.png" width="48"/></td><td width="70">x 4</td></tr>
    <tr><td><img src="https://i.imgur.com/ip72f4t.png" width="48"/></td><td><img src="https://i.imgur.com/ip72f4t.png" width="48"/></td><td><img src="https://i.imgur.com/ip72f4t.png" width="48"/></td><td colspan="3"></td></tr>
</table>

---

## 使用
框選的角落點取決於放置時朝向的方向，共有8種：

<table>
    <tr><td align="center">朝上</td><td align="center">朝下</td></tr>
    <tr>
        <td>
            <table>
                <tr><td align="center" width="70" height="70">西北</td><td align="center" width="70" height="70"></td><td align="center" width="70" height="70">北東</td></tr>
                <tr><td align="center" width="70" height="70"></td><td align="center" width="70" height="70"></td><td align="center" width="70" height="70"></td></tr>
                <tr><td align="center" width="70" height="70">南西</td><td align="center" width="70" height="70"></td><td align="center" width="70" height="70">南東</td></tr>
            </table>
        </td>
        <td>
            <table>
                <tr><td align="center" width="70" height="70">西北</td><td align="center" width="70" height="70"></td><td align="center" width="70" height="70">北東</td></tr>
                <tr><td align="center" width="70" height="70"></td><td align="center" width="70" height="70"></td><td align="center" width="70" height="70"></td></tr>
                <tr><td align="center" width="70" height="70">南西</td><td align="center" width="70" height="70"></td><td align="center" width="70" height="70">南東</td></tr>
            </table>
        </td>
    </tr>
</table>

若要讓[建築藍圖](build_blueprint.md)複製建築則需要先將建築框選起來，且尺寸不超過40x40x40。  
長方體共有8個角，需要讓複製器知道長寬高則最少需要4個角：  

<table>
         <tr><td align="center">完整</td><td colspan="4" align="center"><img src="https://i.imgur.com/tAiFpvW.png" width="200"/><br/>※黃色角代表互動角</td></tr>
         <tr><td align="center">有效</td><td><img src="https://i.imgur.com/eSNuasK.png" width="200"/></td><td><img src="https://i.imgur.com/uBRIJ2Z.png" width="200"/></td><td><img src="https://i.imgur.com/oZw4Bf7.png" width="200"/></td><td><img src="https://i.imgur.com/BBhxgug.png" width="200"/></td></tr>
         <tr><td align="center">無效</td><td><img src="https://i.imgur.com/Jbjb360.png" width="200"/></td><td><img src="https://i.imgur.com/psfXQyP.png" width="200"/></td><td><img src="https://i.imgur.com/egf7uuW.png" width="200"/></td><td><img src="https://i.imgur.com/8zyFdhi.png" width="200"/></td></tr>
</table>

<table>
    <tr><td align="center">概念圖</td><td align="center">遊戲內</td></tr>
    <tr><td><img src="https://i.imgur.com/eSNuasK.png" width="400"/></td><td><img src="https://i.imgur.com/JngGfRt.png" width="400"/></td></tr>
</table>

如果放置正確則看向互動角會顯示白色框線，  

<img src="https://i.imgur.com/6Fmk6E3.png" width="720"/>

慣用手持[建築藍圖](build_blueprint.md)對準互動角`右鍵`可複製建築到藍圖內。