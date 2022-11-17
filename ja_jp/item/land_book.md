# 領地グループの本
泥棒から持ち物を守る。そしてクリーパーはブロックを爆破することができない～素晴らしい～  
[領地ジェネレーター](land_block.md)は無制限にバインド可能！  
モンスターは保護されず、領地で生まれた動物だけが保護される。

## データ
<table>
    <tr>
        <td align="center">有効化なし</td>
        <td align="center">有効化</td>
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
  
## 組合
<table>
    <tr><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td colspan="3"></td></tr>
    <tr><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td><img src="https://i.imgur.com/Oqe8FMm.png" width="48"/></td><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td width="70" align="center"><img src="https://i.imgur.com/VE0KqIE.png" width="40"/></td><td><img src="https://i.imgur.com/Vj4LxUG.png" width="48"/></td><td width="70"></td></tr>
    <tr><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td colspan="3"></td></tr>
</table>

---

## 使用
### 新規作成
慣例的な手持ちの無効になっている領地グループの本は`右クリック`を押すと有効になっている領地グループの本になります。

### 記入領地
慣用的な手持ち有効になっている領地グループの本は、[領地ジェネレーター](land_block.md)を右クリックすることで記入が可能です。

<table>
    <tr><td align="center">未記入</td><td align="center">記入</td></tr>
    <tr><td><img src="https://i.imgur.com/x9meQTF.png" width="400"/></td><td><img src="https://i.imgur.com/h2Kovir.png" width="400"/></td></tr>
</table>

[領地ジェネレーター](land_block.md)が記入になった場合、再利用する前に取り外す必要があります。領地は[ビーコン](https://minecraft.fandom.com/ja/wiki/ビーコン)と同じです。

<img src="https://i.imgur.com/nW7GC4b.png" width="720"/>  

最上部のブロックは[領地ジェネレーター](land_block.md)  
次の4段階のブロックは[領地エネルギー小、領地エネルギー中、領地エネルギー大](land_energy.md)を混在させることができます  
ブロックを4レベルで埋めると、さらに+20%のエネルギーポイントを得ることができます、エネルギーポイント換算式：

<table>
    <tr><td align="center">エネルギー</td><td align="center">点数</td></tr>
    <tr><td align="center">小</td><td align="center">1</td></tr>
    <tr><td align="center">中</td><td align="center">9</td></tr>
    <tr><td align="center">大</td><td align="center">81</td></tr>
</table>

<table>
    <tr><td align="center">4層ブロックは完成していません</td><td><code>チャンク半径</code>=無条件キャリー(平方根(<code>合計点数</code>)/<code>2</code>)-<code>1</code></td></tr>
    <tr><td align="center">4層ブロックは完成</td><td><code>チャンク半径</code>=無条件キャリー(平方根(<code>合計点数</code>x<code>1.2</code>)/<code>2</code>)-<code>1</code></td></tr>
</table>

実際の面積は`ブロック総面積`です=平方(`チャンク半径`+`1`+`チャンク半径`)  
領地は先行する者をカバーすることはできない：  

<table>
    <tr><td><img src="https://i.imgur.com/THNRtuf.png" width="400"/></td><td><img src="https://i.imgur.com/C4waK6f.png" width="400"/></td></tr>
</table>


### 取得領地

有効になっている領地グループの本を誤って紛失してしまった場合でも、回収する方法があります。  
無効になっている領地グループの本を手にした状態で[領地ジェネレーター](land_block.md)を`右クリック`すると、記入になっている領地をブックに戻すことができます。

### 領地名の変更
[金床](https://minecraft.fandom.com/ja/wiki/金床)で有効になっている領地グループの本を任意の名前に変更すると、それに応じて領地グループの名前も変更されます。  
お好きな文字を最大36文字まで入力できます。  
キャッシュ機構により、一部の転用では新しい名前が有効になるまでに最大30秒を要します。

### グループの本

1ページ目と2ページ目は説明文です，3ページ以降`(ALL)=`とすべての[権限](#権限)，書式は`プレイヤー=権限リスト`。  
玩家可以是暱稱或名稱，但編輯完成後一律自動轉換為[暱稱](rename_milk.md)。
```yaml
#最大プレイヤー数200名
#フォーマット:
#  プレイヤー名=権限リスト
#権限:
#  A 防具立て
#  B ボート
#  D ブロックの破壊
#  E コミュニケーション
#  F 額縁
#  G 絵画
#  H ダメージ
#  I ブロックへのアクション
#  L 書見台の閲覧
#  M トロッコ
```
```yaml
#  P ブロックの置き
#  R 所有者
#  S Mobの生成
#  T 回路の起動
#  U バケツ
#  V PVP
#  Y 飛行
```
```yaml
(ALL)=
あなたのニックネーム=ABDEFGHILMPRSTUVY
```

すべてのプレーヤーに飛行を：  
```yaml
(ALL)=Y
あなたのニックネーム=ABDEFGHILMPRSTUVY
```
I_PLAYER プレーヤーに完全な権限を持たせる：  
```yaml
(ALL)=
あなたのニックネーム=ABDEFGHILMPRSTUVY
I_PLAYER=ABDEFGHILMPRSTUVY
```

各行の最初の文字は、コメントであり、内容に関与しないことを示す`#`です  
例えば、次のような行です。
```yaml
(ALL)=A
```
キャンセル
```yaml
#(ALL)=A
```
アップデート後消えます

---

## 権限
- ### A 防具立て
  [防具立て](https://minecraft.fandom.com/ja/wiki/防具立て)の配置、破損、交換
- ### B ボート
  [ボート](https://minecraft.fandom.com/ja/wiki/ボート)の配置、傷害、乗車
- ### D ブロックの破壊
  [ブロック](https://minecraft.fandom.com/ja/wiki/ブロック)の破壊
- ### E コミュニケーション
  [Mob](https://minecraft.fandom.com/ja/wiki/Mob)の給餌
- ### F 額縁
  [額縁](https://minecraft.fandom.com/ja/wiki/額縁)の配置、傷害、変化、回転
- ### G 絵画
  [絵画](https://minecraft.fandom.com/ja/wiki/絵画)の装着、傷害
- ### H ダメージ
  [エンティティ](https://minecraft.fandom.com/ja/wiki/エンティティ)の損傷  
  ※ 僅ダメージ軽減在領地內誕生的動物
- ### I ブロックへのアクション
  [チェスト](https://minecraft.fandom.com/ja/wiki/チェスト)の使用  
  [ビーコン](https://minecraft.fandom.com/ja/wiki/ビーコン)の使用  
  [看板](https://minecraft.fandom.com/ja/wiki/看板)の変更  
  [音符ブロック](https://minecraft.fandom.com/ja/wiki/音符ブロック)の調整
- ### L 書見台の閲覧
  [書見台](https://minecraft.fandom.com/ja/wiki/書見台)の読み物
- ### M トロッコ
  [トロッコ](https://minecraft.fandom.com/ja/wiki/トロッコ)の配置、傷害、乗車
- ### P ブロックの置き
  [ブロック](https://minecraft.fandom.com/ja/wiki/ブロック)の配置
- ### R 所有者
  [領地ジェネレーター](land_block.md)の書き込み、削除  
  領地の権限変更  
  領地エネルギーの配置・撤去  
- ### S Mobの生成
  [スポーンエッグ](https://minecraft.fandom.com/ja/wiki/スポーンエッグ)の使用  
  [友好Mobリード](rope.md)の使用  
  [敵対Mobリード](rope.md)の使用
- ### T 回路の起動
  [トリップワイヤーフック](https://minecraft.fandom.com/ja/wiki/トリップワイヤーフック)のトリガー  
  [トラップチェスト](https://minecraft.fandom.com/ja/wiki/トラップチェスト)の使用  
  [感圧板](https://minecraft.fandom.com/ja/wiki/感圧板)のトリガー
- ### U バケツ
  [バケツ](https://minecraft.fandom.com/ja/wiki/バケツ)の使用  
  [溶岩入りバケツ](https://minecraft.fandom.com/ja/wiki/溶岩入りバケツ)の使用
- ### V PVP
  [プレイヤー](https://minecraft.fandom.com/ja/wiki/プレイヤー)の損傷
- ### Y 飛行
  [領地飛行可能エントラ](land_flying_device.md)は領地で使用することができます