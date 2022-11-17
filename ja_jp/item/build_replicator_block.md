# 建築複製器
こちらもチェックしてみてください[建築青図](build_blueprint.md)。

## データ
<table>
    <tr><td align="end">画像</td><td><img src="https://i.imgur.com/gs5l20b.png" width="128"/></td></tr>
    <tr><td align="end">スタック</td><td>64</td></tr>
    <tr><td align="end">エンチャント</td><td>なし</td></tr>
</table>

---

## 組合
<table>
    <tr><td><img src="https://i.imgur.com/ip72f4t.png" width="48"/></td><td><img src="https://i.imgur.com/ip72f4t.png" width="48"/></td><td><img src="https://i.imgur.com/ip72f4t.png" width="48"/></td><td colspan="3"></td></tr>
    <tr><td><img src="https://i.imgur.com/ip72f4t.png" width="48"/></td><td><img src="https://i.imgur.com/IWZz8YM.png" width="48"/></td><td><img src="https://i.imgur.com/ip72f4t.png" width="48"/></td><td width="70" align="center"><img src="https://i.imgur.com/VE0KqIE.png" width="40"/></td><td><img src="https://i.imgur.com/gs5l20b.png" width="48"/></td><td width="70">x 4</td></tr>
    <tr><td><img src="https://i.imgur.com/ip72f4t.png" width="48"/></td><td><img src="https://i.imgur.com/ip72f4t.png" width="48"/></td><td><img src="https://i.imgur.com/ip72f4t.png" width="48"/></td><td colspan="3"></td></tr>
</table>

---

## 使用
フレームの角の位置は、置く方向によって異なり、8種類あります

<table>
    <tr><td align="center">上方向</td><td align="center">下方向</td></tr>
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

[建築青図](build_blueprint.md)が建物をコピーできるようにするには、まず建物のフレームを選択する必要があり、40x40x40を超えないようにする必要があります。
長方形には8つの角があり、コピー機は少なくとも4つの角の長さ、幅、高さを知る必要がある：

<table>
         <tr><td align="center">フル稼働</td><td colspan="4" align="center"><img src="https://i.imgur.com/tAiFpvW.png" width="200"/><br/>※黄色いコーナーはインタラクティブコーナー</td></tr>
         <tr><td align="center">効く</td><td><img src="https://i.imgur.com/eSNuasK.png" width="200"/></td><td><img src="https://i.imgur.com/uBRIJ2Z.png" width="200"/></td><td><img src="https://i.imgur.com/oZw4Bf7.png" width="200"/></td><td><img src="https://i.imgur.com/BBhxgug.png" width="200"/></td></tr>
         <tr><td align="center">効果なし</td><td><img src="https://i.imgur.com/Jbjb360.png" width="200"/></td><td><img src="https://i.imgur.com/psfXQyP.png" width="200"/></td><td><img src="https://i.imgur.com/egf7uuW.png" width="200"/></td><td><img src="https://i.imgur.com/8zyFdhi.png" width="200"/></td></tr>
</table>

<table>
    <tr><td align="center">コンセプトマップ</td><td align="center">ゲーム内</td></tr>
    <tr><td><img src="https://i.imgur.com/eSNuasK.png" width="400"/></td><td><img src="https://i.imgur.com/JngGfRt.png" width="400"/></td></tr>
</table>

正しく配置されると、インタラクティブコーナーを覗き込んだときに白いボックスが表示されます，  

<img src="https://i.imgur.com/6Fmk6E3.png" width="720"/>

慣習的に手で持っている[建築青図](build_blueprint.md)は、インタラクティブコーナーで`右クリック`することで設計図にコピーすることができます。