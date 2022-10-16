# 領地群組之書
保護好自己的家當，避免遭小偷。而且苦力怕還炸不壞～真是太棒了～  
可以綁定無限個[領地產生器](land_block.md)！

## 資料
<table>
    <tr>
        <td align="center">未啟用</td>
        <td align="center">已啟用</td>
    </tr>
    <tr>
        <td>
            <table>
                <tr><td>圖像</td><td><img src="https://i.imgur.com/Vj4LxUG.png" width="128"/></td></tr>
                <tr><td>空間</td><td><code>land_system_book_empty</code></td></tr>
                <tr><td>翻譯</td><td><code>landsystem.item.land_system_book_empty</code></td></tr>
                <tr><td>材質</td><td><a href="https://minecraft.fandom.com/zh/wiki/書">書</a></td></tr>
                <tr><td>堆疊</td><td>64</td></tr>
                <tr><td>配方</td><td><a href="https://minecraft.fandom.com/zh/wiki/合成/雜項配方">雜項</a></td></tr>
                <tr><td>附魔</td><td>無</td></tr>
                <tr><td>新增</td><td>2020-07-10</td></tr>
            </table>
        </td>
        <td>
            <table>
                <tr><td>圖像</td><td><img src="https://i.imgur.com/duGvD3y.png" width="128"/></td></tr>
                <tr><td>空間</td><td><code>land_system_book</code></td></tr>
                <tr><td>翻譯</td><td><code>landsystem.item.land_system_book</code></td></tr>
                <tr><td>材質</td><td><a href="https://minecraft.fandom.com/zh/wiki/書和羽毛筆">書和羽毛筆</a></td></tr>
                <tr><td>堆疊</td><td>1</td></tr>
                <tr><td>配方</td><td>無</td></tr>
                <tr><td>附魔</td><td>無</td></tr>
                <tr><td>新增</td><td>2020-07-10</td></tr>
            </table>
        </td>
    </tr>
</table>
  
---
  
## 合成
<table>
    <tr><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td colspan="3"></td></tr>
    <tr><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td><img src="https://i.imgur.com/Oqe8FMm.png" width="48"/></td><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td width="70" align="center"><img src="https://i.imgur.com/VE0KqIE.png" width="40"/></td><td><img src="https://i.imgur.com/Vj4LxUG.png" width="48"/></td><td width="70"></td></tr>
    <tr><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td colspan="3"></td></tr>
</table>
  
---

## 使用
### 創建新的
慣用手持未啟用的領地群組之書按右鍵，會變成已啟用的領地群組之書

### 產生領地
慣用手持已啟用的領地群組之書對準[領地產生器](land_block.md)右鍵，可以寫入。  
如果[領地產生器](land_block.md)已經被寫入，需要先拆除才可重新使用。

### 獲取領地
如果不慎遺失了唯一的已啟用的領地群組之書，依然有方法取回。  
慣用手持未啟用的領地群組之書對著[領地產生器](land_block.md)右鍵，可將已寫入的領地群組還原到書中。

### 更改名稱
將已啟用的領地群組之書在[鐵砧](https://minecraft.fandom.com/zh/wiki/鐵砧)改成想要的名稱，領地群組的名稱會跟著改變。  
可輸入最多36個任意字元。  
由於快取機制，部份分流需要等待最久30秒新名稱才會生效。

### 群組之書
第一、二頁為說明，第三頁開始`(ALL)=`及全部[權限](#權限)，格式為`玩家=權限清單`。  
玩家可以是暱稱或名稱，但編輯完成後一律自動轉換為[暱稱](rename_milk.md)。
```yaml
#最大限制200名玩家
#格式:
#  玩家名稱=權限清單
#權限:
#  A 盔甲座
#  B 船
#  D 破壞方塊
#  E 實體互動
#  F 展示框
#  G 畫框
#  H 傷害實體
#  I 方塊互動
#  L 閱讀講座書
#  M 礦車
```
```yaml
#  P 放置方塊
#  R 擁有者
#  S 生成實體
#  T 觸發機關
#  U 水桶
#  V PVP
#  Y 飛行
```
```yaml
(ALL)=
你的玩家暱稱=ABDEFGHILMPRSTUVY
```
如果想讓全部玩家都能飛行  
```yaml
(ALL)=Y
你的玩家暱稱=ABDEFGHILMPRSTUVY
```
如果想讓 I_PLAYER 玩家擁有全部的權限  
```yaml
(ALL)=
你的玩家暱稱=ABDEFGHILMPRSTUVY
I_PLAYER=ABDEFGHILMPRSTUVY
```

---

## 權限
- ### A 盔甲座
  [盔甲座](https://minecraft.fandom.com/zh/wiki/盔甲座)的放置、傷害、換裝
- ### B 船
  [船](https://minecraft.fandom.com/zh/wiki/船)的放置、傷害、乘坐
- ### D 破壞方塊
  [方塊](https://minecraft.fandom.com/zh/wiki/方塊)的破壞
- ### E 實體互動
  [實體](https://minecraft.fandom.com/zh/wiki/動物)的餵食
- ### F 展示框
  [物品展示框](https://minecraft.fandom.com/zh/wiki/物品展示框)的放置、傷害、換物、旋轉
- ### G 畫框
  [畫](https://minecraft.fandom.com/zh/wiki/畫)的放置、傷害
- ### H 傷害實體
  [實體](https://minecraft.fandom.com/zh/wiki/實體)的損傷  
  ※ 僅保護在領地內誕生的動物
- ### I 方塊互動
  [儲物箱](https://minecraft.fandom.com/zh/wiki/儲物箱)的使用  
  [烽火台](https://minecraft.fandom.com/zh/wiki/烽火台)的使用  
  [告示牌](https://minecraft.fandom.com/zh/wiki/告示牌)的梗改  
  [音階盒](https://minecraft.fandom.com/zh/wiki/音階盒)的調整
- ### L 閱讀講座書
  [講台](https://minecraft.fandom.com/zh/wiki/講台)的閱覽
- ### M 礦車
  [船](https://minecraft.fandom.com/zh/wiki/船)的放置、傷害、乘坐
- ### P 放置方塊
  [方塊](https://minecraft.fandom.com/zh/wiki/方塊)的放置
- ### R 擁有者
  [領地產生器](land_block.md)的寫入、拆除  
  更改領地權限
  領地能量的放置、拆除
- ### S 生成實體
  [生怪蛋](https://minecraft.fandom.com/zh/wiki/生怪蛋)的使用  
  [友善生物收納繩](amiability_rope.md)的使用  
  [邪惡生物收納繩](malicious_rope.md)的使用
- ### T 觸發機關
  [絆線鉤](https://minecraft.fandom.com/zh/wiki/絆線鉤)的觸發  
  [陷阱儲物箱](https://minecraft.fandom.com/zh/wiki/陷阱儲物箱)的使用  
  [壓力板](https://minecraft.fandom.com/zh/wiki/壓力板)的觸發
- ### U 水桶
  [水桶](https://minecraft.fandom.com/zh/wiki/水桶)的使用  
  [熔岩桶](https://minecraft.fandom.com/zh/wiki/熔岩桶)的使用
- ### V PVP
  [玩家](https://minecraft.fandom.com/zh/wiki/玩家)的損傷
- ### Y 飛行
  領地內可使用[領地飛行鞘翅](land_flying_device.md)