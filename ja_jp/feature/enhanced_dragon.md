[← ホームに戻る](../)
# エンド・ドラゴン（強化版）

## データ
<table>
    <tr><td align="end">ヘルス（体力）</td><td>2000</td></tr>
</table>

---

## ビヘイビア（行動）
### 現在のレベル
ヘルスは10段階に分かれ、1段階あたり10%のヘルスを表しており、レベルは以下の式で算出されます：10×切り捨て（残りヘルス÷200）。つまり、1から10のレベルがあり、レベルを1つ上げるごとに水晶が再召集されます。
### 爆発の光柱
爆発の光柱は、座標が`（0,0）`のエンドにおいて、半径`20`の範囲内に14+レベル個生成されます。各光柱は`56`秒生存し、3～10秒ごとにランダムな方向に移動します。距離`6`ブロック以内のプレイヤーに（`7.0`+`0.1`×レベル）×（`1.0`×（`距離`×`2.0`）÷`4.0`）のダメージを与えます。
### クリスタルの脈動
クリスタルが破壊されると、周囲`4`ブロック半径内に10個の爆発の光柱が生成され、`(0,0)`中心点に向かって徐々に近づいていき、`14`ブロック半径内に20個の爆発の光柱が生成されます。

---

## ドロップ
エンド・ゲートウェイ上に。
<table>
    <tr><td align="center">94%</td><td align="center" rowspan="3"><img src="https://i.imgur.com/0iqFoY6.png" width="48"/></td><td colspan="2"><img src="https://i.imgur.com/wl43BjZ.png" width="48"/></td></tr>
    <tr><td align="center">5%</td><td align="center" rowspan="2"><a href="../item/dragon_tooth.md"><img src="https://i.imgur.com/ZJn6ZOj.png" width="48"/></a></td><td><img src="https://i.imgur.com/wl43BjZ.png" width="48"/></td></tr>
    <tr><td align="center">1%</td><td align="center"><a href="../item/dragon_blood_tooth.md"><img src="https://i.imgur.com/DWX8hfU.png" width="48"/></a></td></tr>
</table>

---

## 制限
[エンドポータル](https://minecraft.fandom.com/ja/wiki/ジ・エンド・ポータル)半径`200`ブロック内で領地飛行](../item/land_flying_device.md)不可。
