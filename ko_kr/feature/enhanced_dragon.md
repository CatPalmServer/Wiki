[← 홈으로](../)
# 강화 된 엔드 드래곤

## 데이터
<table>
    <tr><td align="end">생명력</td><td>2000</td></tr>
</table>

---

## 행동
### 현재 레벨
체력은 10 등분으로 구분되며, 각 등분은 체력의 10%를 나타내며, 레벨은 `10` × 내림 (남은 체력 / `200`)으로 계산됩니다. 따라서 레벨은 1에서 10까지이며, 레벨을 1 증가시킬 때마다 크리스탈이 재소환됩니다.
### 폭발 빔
엔드 포탈 좌표`(0,0)`를 중심으로 반지름`20`블록 이상 떨어진 곳에 폭발 기둥이 최대`14`개 생성됩니다. 각 기둥은 `56`초 동안 살아있으며, `3`~`10`초마다 무작위 방향으로 이동합니다. 이 기둥은 거리 `6`블록 내에 있는 플레이어에게 (`7.0`+`0.1`x`레벨`)x(`1.0`-(`거리`-`2.0`)/`4.0`)의 피해를 입힙니다.
### 크리스탈 파동
크리스탈이 파괴되면 반경 `4`블록 이내에 폭발 기둥이 최대 `10`개 생성되며, 중심 좌표`(0,0)`으로부터 서서히 이동하다가 중심 좌표에 도달하면 반경 `14`블록 이내에 더 많은 폭발 기둥이 생성됩니다.

---

## 드롭
엔드 게이트웨이 위에。
<table>
    <tr><td align="center">94%</td><td align="center" rowspan="3"><img src="https://i.imgur.com/0iqFoY6.png" width="48"/></td><td colspan="2"><img src="https://i.imgur.com/wl43BjZ.png" width="48"/></td></tr>
    <tr><td align="center">5%</td><td align="center" rowspan="2"><a href="../item/dragon_tooth.md"><img src="https://i.imgur.com/ZJn6ZOj.png" width="48"/></a></td><td><img src="https://i.imgur.com/wl43BjZ.png" width="48"/></td></tr>
    <tr><td align="center">1%</td><td align="center"><a href="../item/dragon_blood_tooth.md"><img src="https://i.imgur.com/DWX8hfU.png" width="48"/></a></td></tr>
</table>

---

## 제한
[엔드 게이트웨이](https://minecraft.fandom.com/ko/wiki/엔드_게이트) 반경`200`블록 이내에서는 [랜드 비행장치](../item/land_flying_device.md) 사용이 제한됩니다.
