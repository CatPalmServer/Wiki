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
由於快取機制，部份分流需要等待最久30秒新名稱才會生效。

### 群組之書
預設內容
```properties
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
#  P 放置方塊
#  R 擁有者
#  S 生成實體
#  T 觸發機關
#  U 水桶
#  V PVP
#  Y 飛行
(ALL)=
旋=ABDEFGHILMPRSTUVY
```

---

## 權限
