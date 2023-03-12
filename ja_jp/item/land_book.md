[← ホームに戻る](../)
# 領地グループの本
自分の家財道具を守り、泥棒から身を守ってください。クリーパーの爆発にも耐えます～とても優れています～
無限の<a href="land_block.md">領地ジェネレーター</a>をバインドすることができます！
モンスターは保護されず、領地内で生まれた動物だけが保護されます。

## データ
<table>
    <tr>
        <td align="center">未使用</td>
        <td align="center">使用済み</td>
    </tr>
    <tr>
        <td>
            <table>
                <tr><td align="end">画像</td><td><img src="https://i.imgur.com/Vj4LxUG.png" width="128"/></td></tr>
                <tr><td align="end">スタック</td><td>64</td></tr>
                <tr><td align="end">エンチャント</td><td>なし</td></tr>
            </table>
        </td>
        <td>
            <table>
                <tr><td align="end">画像</td><td><img src="https://i.imgur.com/duGvD3y.png" width="128"/></td></tr>
                <tr><td align="end">スタック</td><td>1</td></tr>
                <tr><td align="end">エンチャント</td><td>なし</td></tr>
            </table>
        </td>
    </tr>
</table>

---
  
## クラフト
<table>
    <tr><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td colspan="3"></td></tr>
    <tr><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td><img src="https://i.imgur.com/Oqe8FMm.png" width="48"/></td><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td width="70" align="center"><img src="https://i.imgur.com/VE0KqIE.png" width="40"/></td><td><img src="https://i.imgur.com/Vj4LxUG.png" width="48"/></td><td width="70"></td></tr>
    <tr><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td colspan="3"></td></tr>
</table>

---

## 使用方法
### 新しいものを作る
未起動の領地グループの本を持って右クリックすると、起動済みの領地グループの本になります。

### 領地を生成する
起動済みの<a href="land_block.md">領地ジェネレーター</a>を持って右クリックすることで、領地を書き込むことができます。

<table>
    <tr><td align="center">未書き込み</td><td align="center">書き込み済み</td></tr>
    <tr><td><img src="https://i.imgur.com/x9meQTF.png" width="400"/></td><td><img src="https://i.imgur.com/h2Kovir.png" width="400"/></td></tr>
</table>

もし領地発生装置（land_block.md）がすでに書き込まれている場合は、再使用する前に取り除く必要があります。領地の配置方法は、烽火台（https://minecraft.fandom.com/ja/wiki/ビーコン

<img src="https://i.imgur.com/nW7GC4b.png" width="720"/>  

頂部ブロックは領地発生装置（land_block.md）です。
下4層は領地小エネルギー、領地中エネルギー、領地大エネルギー（land_energy.md）を混在させることができます。
4層まで埋まっている場合、追加で+20%のエネルギーポイントを獲得します。エネルギーポイントの変換式：

<table>
    <tr><td align="center">エネルギー</td><td align="center">ポイント</td></tr>
    <tr><td align="center">小</td><td align="center">1</td></tr>
    <tr><td align="center">中</td><td align="center">9</td></tr>
    <tr><td align="center">大</td><td align="center">81</td></tr>
</table>

<table>
    <tr><td align="center">4層未満</td><td><code>ブロック半径</code>=切り上げ(平方根(<code>総ポイント数</code>)/<code>2</code>)-<code>1</code></td></tr>
    <tr><td align="center">4層まで埋まっている</td><td><code>ブロック半径</code>=切り上げ(平方根(<code>総ポイント数</code>x<code>1.2</code>)/<code>2</code>)-<code>1</code></td></tr>
</table>

実際の面積は、`総ブロック面積`=平方(`ブロック半径`+`1`+`ブロック半径`)です。
自分よりも早く領地を占めたプレイヤーの領地を上書きすることはできません。：  

<table>
    <tr><td><img src="https://i.imgur.com/THNRtuf.png" width="400"/></td><td><img src="https://i.imgur.com/C4waK6f.png" width="400"/></td></tr>
</table>


### 領地を獲得する
有効になっている領地グループの本を誤って紛失した場合でも、取り戻す方法があります。
アクティブでない領地グループの書を持って、領地ブロック (land_block.md) を右クリックすると、書に書かれている領地グループを復元できます。

### 名前を変更する
アクティブな領地グループの書を鉄砧 (https://minecraft.fandom.com/ja/wiki/金床) でクリックして、名前を変更することができます。領地グループの名前も変更されます。
最大36文字まで入力できます。
一部の変更は、キャッシュの仕組みにより、30秒以上かかる場合があります。

### グループの書
1ページ目と2ページ目は説明で、3ページ目以降には「ALL」と「#権限」の権限リストが表示されます。フォーマットは「プレイヤー=権限リスト」となっています。
プレイヤーはニックネームまたは名前で指定できますが、編集後にはすべて自動的にニックネームに変換されます。
```yaml
最大200人まで許容されます。
#フォーマット:
プレイヤー名=権限リスト
#権限:
#  A アーマースタンド
#  B ボート
#  D ブロック破壊
#  E エンティティのインタラクション
#  F アイテムフレーム
#  G 絵画
#  H エンティティへのダメージ
#  I ブロックのインタラクション
#  L 講義ノートの読み込み
#  M マインカート
```
```yaml
#  P ブロックの設置
#  R オーナー
#  S 生成されたエンティティ
#  T トリガー
#  U バケツ
#  V PVP
#  Y 飛行
```
```yaml
(ALL)=
あなたのプレイヤー名=ABDEFGHILMPRSTUVY
```

全プレイヤーの飛行を可能にする：  
```yaml
(ALL)=Y
あなたのプレイヤー名=ABDEFGHILMPRSTUVY
```
I_PLAYER プレイヤーにすべての権限を与える：
```yaml
(ALL)=
あなたのプレイヤー名=ABDEFGHILMPRSTUVY
I_PLAYER=ABDEFGHILMPRSTUVY
```

各行の最初の文字が `#` の場合、コメントであり内容には影響しない
下の行をコメントアウトすると、更新後にこの行は自動的に消えます
```yaml
(ALL)=A
```
[防具立て](https://minecraft.fandom.com/ja/wiki/防具立て)の設置、ダメージ、装備
```yaml
#(ALL)=A
```
[ボート](https://minecraft.fandom.com/ja/wiki/ボート)の設置、ダメージ、乗る

---

## 権限
- ### A アーマースタンド
  [ブロック](https://minecraft.fandom.com/ja/wiki/ブロック)の破壊
- ### B ボート
  [エンティティ](https://minecraft.fandom.com/ja/wiki/動物)の餌付け
- ### D ブロック破壊
  [アイテムフレーム](https://minecraft.fandom.com/ja/wiki/アイテムフレーム)の設置、ダメージ、アイテムの変更、回転
- ### E エンティティのインタラクション
  [絵画](https://minecraft.fandom.com/ja/wiki/絵画)の設置、ダメージ
- ### F アイテムフレーム
  [エンティティ](https://minecraft.fandom.com/ja/wiki/エンティティ)のダメージ
- ### G 絵画
  領地内で誕生した動物だけを保護する
- ### H エンティティへのダメージ
  ?
  ※ ?
- ### I ブロックのインタラクション
  [チェスト](https://minecraft.fandom.com/ja/wiki/チェスト)の使用
  [ 烽火台 ] (https://minecraft.fandom.com/ja/wiki/ビーコン) の使用
  [ 看板 ] (https://minecraft.fandom.com/ja/wiki/看板) の変更
  [ ノートブロック ] (https://minecraft.fandom.com/ja/wiki/ノートブロック) の調整
- ### L 講義ノートの読み込み
  [ 講壇 ] (https://minecraft.fandom.com/ja/wiki/講義台) の閲覧
- ### M マインカート
  [ マインカート ] (https://minecraft.fandom.com/ja/wiki/マインカート) の設置、ダメージ、乗車
- ### P ブロックの設置
  [ ブロック ] (https://minecraft.fandom.com/ja/wiki/ブロック) の設置
- ### R オーナー
  [ 領地生成機 ] (land_block.md) の書き込み、解除
  領地権限の変更
  領地エネルギーの設置、解除
- ### S 生成されたエンティティ
  [ スポーンエッグ ] (https://minecraft.fandom.com/ja/wiki/スポーンエッグ) の使用
  [ 友好的な生物の収納ロープ ] (rope.md) の使用
  [ 敵対的な生物の収納ロープ ] (rope.md) の使用
- ### T トリガー
  [ フックショット ] (https://minecraft.fandom.com/ja/wiki/フックショット) の発動
  [ トラップチェスト ] (https://minecraft.fandom.com/ja/wiki/トラップチェスト) の使用
  [ プレッシャープレート ] (https://minecraft.fandom.com/ja/wiki/プレッシャープレート) の発動
- ### U バケツ
  [ 水バケツ ] (https://minecraft.fandom.com/ja/wiki/水バケツ) の使用
  [ 溶岩バケツ ] (https://minecraft.fandom.com/ja/wiki/溶岩バケツ) の使用
- ### V PVP
  [ プレイヤー ] (https://minecraft.fandom.com/ja/wiki/プレイヤー) のダメージ
- ### Y 飛行
  [ 領地フライングデバイス ] (land_flying_device.md) の飛行
  [猫饲料](../feature/cat_bowl.md)の切り替え観察者
  [猫饲料](../feature/cat_bowl.md)の磁石によるアイテム吸引
  

---

## アクティブ
以下の行動でアクティブ度が上昇します：
- 実体取引、毎回+`100`
- ブロック破壊、ブロック設置、ブロック更新、毎回+`40`
- アイテム拾い、アイテム捨て、容器取得、容器収納、毎回+`20`
- 実体ダメージ、毎回+`10`
- [猫饲料](../feature/cat_bowl.md)プレイヤー存在、毎秒+`4`
- プレイヤー存在、毎秒+`1`

各区画のアクティブ度上限は`200,000`であり、土地内のアクティブ度が毎`5,000`ごとに`1`ポイントを保持できます[領地エネルギー](land_energy.md)。
12ヶ月ごとに、保持できる[領地エネルギー](land_energy.md)ポイントが検証されます。全体の`20`%未満であれば、全てが破壊されます。それ以外の場合、次のことが起こります：
- 保持できなかった[領地エネルギー](land_energy.md)は破壊されます。
- 保持できる[領地エネルギー](land_energy.md)がない場合、[領地産生器](land_block.md)と共に破壊されます。

アクティブな領地産生器が指し示されると、0~999%のアクティブ度の参考が表示されます。
公式=最小値(`999`,切り捨て(`現在の総活性度`/((`現在時刻`-`前回のチェックまたは作成時刻`)/`6ヶ月時間`)/`5000.0`/`現在の総エネルギーポイント数`x`100.0`))
通常、`100`%以上の場合、安全で損傷はありません。
