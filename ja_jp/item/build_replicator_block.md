[← ホームに戻る](../)
# 建築複製器
藍图模块よりも便利でちょっとしたもので、建築のブループリント(build_blueprint.md)を見ることもできます。

## データ
<table>
    <tr><td align="end">画像</td><td><img src="https://i.imgur.com/gs5l20b.png" width="128"/></td></tr>
    <tr><td align="end">スタック</td><td>64</td></tr>
    <tr><td align="end">エンチャント</td><td>なし</td></tr>
</table>

---

## クラフト
<table>
    <tr><td><img src="https://i.imgur.com/ip72f4t.png" width="48"/></td><td><img src="https://i.imgur.com/ip72f4t.png" width="48"/></td><td><img src="https://i.imgur.com/ip72f4t.png" width="48"/></td><td colspan="3"></td></tr>
    <tr><td><img src="https://i.imgur.com/ip72f4t.png" width="48"/></td><td><img src="https://i.imgur.com/IWZz8YM.png" width="48"/></td><td><img src="https://i.imgur.com/ip72f4t.png" width="48"/></td><td width="70" align="center"><img src="https://i.imgur.com/VE0KqIE.png" width="40"/></td><td><img src="https://i.imgur.com/gs5l20b.png" width="48"/></td><td width="70">x 4</td></tr>
    <tr><td><img src="https://i.imgur.com/ip72f4t.png" width="48"/></td><td><img src="https://i.imgur.com/ip72f4t.png" width="48"/></td><td><img src="https://i.imgur.com/ip72f4t.png" width="48"/></td><td colspan="3"></td></tr>
</table>

---

## 使用方法
選択した角の位置は、配置時の方向に依存し、8種類あります：

<table>
    <tr><td align="center">上向き</td><td align="center">下向き</td></tr>
    <tr>
        <td>
            <table>
                <tr><td align="center" width="70" height="70">北西</td><td align="center" width="70" height="70"></td><td align="center" width="70" height="70">北東</td></tr>
                <tr><td align="center" width="70" height="70"></td><td align="center" width="70" height="70"></td><td align="center" width="70" height="70"></td></tr>
                <tr><td align="center" width="70" height="70">南西</td><td align="center" width="70" height="70"></td><td align="center" width="70" height="70">南東</td></tr>
            </table>
        </td>
        <td>
            <table>
                <tr><td align="center" width="70" height="70">北西</td><td align="center" width="70" height="70"></td><td align="center" width="70" height="70">北東</td></tr>
                <tr><td align="center" width="70" height="70"></td><td align="center" width="70" height="70"></td><td align="center" width="70" height="70"></td></tr>
                <tr><td align="center" width="70" height="70">南西</td><td align="center" width="70" height="70"></td><td align="center" width="70" height="70">南東</td></tr>
            </table>
        </td>
    </tr>
</table>

建築ブループリント(build_blueprint.md)を複製する場合、まず建築物を選択して、サイズが40x40x40を超えないようにする必要があります。
直方体には8つの角があり、サイズを知らせるためには最低でも4つの角が必要です：

<table>
         <tr><td align="center">完全なもの</td><td colspan="4" align="center"><img src="https://i.imgur.com/tAiFpvW.png" width="200"/><br/>※黄色の角は交互の角を表します</td></tr>
         <tr><td align="center">有効</td><td><img src="https://i.imgur.com/eSNuasK.png" width="200"/></td><td><img src="https://i.imgur.com/uBRIJ2Z.png" width="200"/></td><td><img src="https://i.imgur.com/oZw4Bf7.png" width="200"/></td><td><img src="https://i.imgur.com/BBhxgug.png" width="200"/></td></tr>
         <tr><td align="center">無効</td><td><img src="https://i.imgur.com/Jbjb360.png" width="200"/></td><td><img src="https://i.imgur.com/psfXQyP.png" width="200"/></td><td><img src="https://i.imgur.com/egf7uuW.png" width="200"/></td><td><img src="https://i.imgur.com/8zyFdhi.png" width="200"/></td></tr>
</table>

<table>
    <tr><td align="center">概念図</td><td align="center">ゲーム内</td></tr>
    <tr><td><img src="https://i.imgur.com/eSNuasK.png" width="400"/></td><td><img src="https://i.imgur.com/JngGfRt.png" width="400"/></td></tr>
</table>

正しく配置されている場合、交互の角を向いていると白い枠線が表示されます，  

<img src="https://i.imgur.com/6Fmk6E3.png" width="720"/>

建築ブループリント(build_blueprint.md)を使って建築物を複製するには、交互の角に向かって建築物を右クリックして複製します。
