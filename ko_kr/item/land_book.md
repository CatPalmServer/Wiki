[← 홈으로](../)
# 토지 그룹의 책
자신의 소지품을 보호하여 도둑에게 노출되지 않도록 합니다. 또한 크리퍼도 폭발시키지 못하므로 정말 좋습니다~
무제한의 [토지 생성기](land_block.md)를 바인딩 할 수 있습니다!
몬스터는 보호되지 않으며, 영토 내에서만 태어난 동물만 보호됩니다.

## 데이터
<table>
    <tr>
        <td align="center">사용 불가</td>
        <td align="center">사용 가능</td>
    </tr>
    <tr>
        <td>
            <table>
                <tr><td align="end">이미지</td><td><img src="https://i.imgur.com/Vj4LxUG.png" width="128"/></td></tr>
                <tr><td align="end">스택</td><td>64</td></tr>
                <tr><td align="end">인챈트</td><td>없음</td></tr>
            </table>
        </td>
        <td>
            <table>
                <tr><td align="end">이미지</td><td><img src="https://i.imgur.com/duGvD3y.png" width="128"/></td></tr>
                <tr><td align="end">스택</td><td>1</td></tr>
                <tr><td align="end">인챈트</td><td>없음</td></tr>
            </table>
        </td>
    </tr>
</table>

---
  
## 제작
<table>
    <tr><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td colspan="3"></td></tr>
    <tr><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td><img src="https://i.imgur.com/Oqe8FMm.png" width="48"/></td><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td width="70" align="center"><img src="https://i.imgur.com/VE0KqIE.png" width="40"/></td><td><img src="https://i.imgur.com/Vj4LxUG.png" width="48"/></td><td width="70"></td></tr>
    <tr><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td colspan="3"></td></tr>
</table>

---

## 사용
### 새로 만들기
비활성화된 영토 그룹 북을 사용하여 오른쪽 클릭하면 활성화된 영토 그룹 북이 됩니다.

### 영토 생성
활성화된 영토 그룹 북을 사용하여 [영토 생성기](land_block.md)에 대해 오른쪽 클릭하면 작성할 수 있습니다.

<table>
    <tr><td align="center">미작성</td><td align="center">작성됨</td></tr>
    <tr><td><img src="https://i.imgur.com/x9meQTF.png" width="400"/></td><td><img src="https://i.imgur.com/h2Kovir.png" width="400"/></td></tr>
</table>

만약 [영토 생성기](land_block.md)가 이미 작성되었다면, 재사용하기 전에 제거해야 합니다. 영토 배치 방법은 [신호 탑](https://minecraft.fandom.com/ko/wiki/신호_탑)과 동일합니다.

<img src="https://i.imgur.com/nW7GC4b.png" width="720"/>  

상단 블록은 [영토 생성기](land_block.md)입니다.
하위 4개 레벨은 [영토 작은 에너지, 영토 중간 에너지, 영토 큰 에너지](land_energy.md)를 혼합할 수 있습니다.
4층이 가득 차면 추가 20% 에너지 포인트가 제공됩니다. 에너지 포인트 변환 공식:

<table>
    <tr><td align="center">에너지</td><td align="center">포인트 수</td></tr>
    <tr><td align="center">작음</td><td align="center">1</td></tr>
    <tr><td align="center">중간</td><td align="center">9</td></tr>
    <tr><td align="center">큼</td><td align="center">81</td></tr>
</table>

<table>
    <tr><td align="center">4층이 가득 차지 않음</td><td><code>블록 반경</code>=올림(루트(<code>총 포인트</code>)/<code>2</code>)-<code>1</code></td></tr>
    <tr><td align="center">4층이 가득 참</td><td><code>블록 반경</code>=올림(루트(<code>총 포인트</code>x<code>1.2</code>)/<code>2</code>)-<code>1</code></td></tr>
</table>

실제 면적은 `총 블록 면적`=제곱(`블록 반경`+`1`+`블록 반경`)입니다.
다른 사람이 이미 차지한 지역을 덮어쓰지 않습니다:  

<table>
    <tr><td><img src="https://i.imgur.com/THNRtuf.png" width="400"/></td><td><img src="https://i.imgur.com/C4waK6f.png" width="400"/></td></tr>
</table>


### 지역을 획득합니다.
이미 사용 중인 지역 그룹 책을 실수로 분실한 경우에도 복구할 수 있습니다.
미사용 상태의 지역 그룹 책을 손에 들고 땅 블록을 우클릭하면, 책에 기록된 지역 그룹이 복원됩니다.

### 이름을 변경합니다.
사용 중인 지역 그룹 책을 모루 위에 올려 이름을 변경하면, 지역 그룹의 이름도 함께 변경됩니다.
최대 36자의 아무 문자열도 입력할 수 있습니다.
캐시 메커니즘 때문에 일부 경로는 새 이름이 최대 30초까지 적용되기를 기다려야 합니다.

### 지역 그룹 책
첫 번째와 두 번째 페이지는 설명입니다. 세 번째 페이지부터 ALL(모두) 및 모든 권한에 대한 권한 목록이 있습니다. 형식은 플레이어 = 권한 목록입니다.
플레이어는 닉네임 또는 이름이 될 수 있지만, 편집이 완료되면 모두 자동으로 닉네임으로 변환됩니다.
```yaml
최대 200명의 플레이어 제한
#형식:
플레이어 이름 = 권한 목록
#권한:
#  A 갑옷 거치대
#  B 배
#  D 블록 파괴
#  E 엔티티 상호 작용
#  F 아이템 액자
#  G 그림 액자
#  H 엔티티 공격
#  I 블록 상호 작용
#  L 강의책 읽기
#  M 광산 수레
```
```yaml
#  P 블록 설치
#  R 소유자
#  S 엔티티 생성
#  T 트리거 작동
#  U 물 양동이
#  V PVP
#  Y 비행
```
```yaml
(ALL)=
당신의 플레이어 닉네임=ABDEFGHILMPRSTUVY
```

모든 플레이어가 비행할 수 있도록합니다:  
```yaml
(ALL)=Y
당신의 플레이어 닉네임=ABDEFGHILMPRSTUVY
```
I_PLAYER 플레이어가 모든 권한을 갖도록합니다.
```yaml
(ALL)=
당신의 플레이어 닉네임=ABDEFGHILMPRSTUVY
I_PLAYER=ABDEFGHILMPRSTUVY
```

각 행의 첫 번째 문자가 `#` 인 경우 주석으로 처리되고 내용에 참여하지 않습니다.
예를 들어 아래 행을
```yaml
(ALL)=A
```
주석 처리
```yaml
#(ALL)=A
```
하면이 행은 자동으로 사라집니다.

---

## 권한
- ### A 갑옷 거치대
  [ 갑옷 거치대 ] (https://minecraft.fandom.com/ko/wiki/갑옷_거치대)의 배치, 손상, 의복 교체
- ### B 배
  [ 보트 ] (https://minecraft.fandom.com/ko/wiki/보트)의 배치, 손상, 승선
- ### D 블록 파괴
  [ 블록 ] (https://minecraft.fandom.com/ko/wiki/블록)의 파괴
- ### E 엔티티 상호 작용
  [ 엔티티 ] (https://minecraft.fandom.com/ko/wiki/동물)의 사료 주기
- ### F 아이템 액자
  [ 아이템 표시 장 ] (https://minecraft.fandom.com/ko/wiki/아이템_액자)의 배치, 손상, 아이템 교체, 회전
- ### G 그림 액자
  [ 그림 ] (https://minecraft.fandom.com/ko/wiki/그림)의 배치, 손상
- ### H 엔티티 공격
  [ 엔티티 ] (https://minecraft.fandom.com/ko/wiki/엔티티)의 손상
  ※ 영토 내에서 태어난 동물 만 보호합니다.
- ### I 블록 상호 작용
  [ 창고 ] (https://minecraft.fandom.com/ko/wiki/창고)의 사용
  [ 봉화대 ] (https://minecraft.fandom.com/ko/wiki/신호의_불)의 사용
  [ 공지판 ] (https://minecraft.fandom.com/ko/wiki/갱신_표지판)의 수정
  [ 음악 상자 ] (https://minecraft.fandom.com/ko/wiki/노래방_상자)의 조정
- ### L 강의책 읽기
  [ 강의 대 ] (https://minecraft.fandom.com/ko/wiki/강의_대)의 열람
- ### M 광산 수레
  [광차](https://minecraft.fandom.com/ko/wiki/광차)의 설치, 피해, 탑승
- ### P 블록 설치
  [블록](https://minecraft.fandom.com/ko/wiki/블록)의 설치
- ### R 소유자
  [영지 생성기](land_block.md)의 기록, 철거
  영지 권한 변경
  영지 에너지의 설치, 철거
- ### S 엔티티 생성
  [스폰 에그](https://minecraft.fandom.com/ko/wiki/스폰_알)의 사용
  [우호적인 동물 수집 줄](rope.md)의 사용
  [악의적인 동물 수집 줄](rope.md)의 사용
- ### T 트리거 작동
  [그물갈고리](https://minecraft.fandom.com/ko/wiki/그물_갈고리)의 작동
  [함정 상자](https://minecraft.fandom.com/ko/wiki/함정_상자)의 사용
  [압력판](https://minecraft.fandom.com/ko/wiki/압력판)의 작동
- ### U 물 양동이
  [양동이](https://minecraft.fandom.com/ko/wiki/양동이)의 사용
  [용암 양동이](https://minecraft.fandom.com/ko/wiki/용암_양동이)의 사용
- ### V PVP
  [플레이어](https://minecraft.fandom.com/ko/wiki/플레이어)의 손상
- ### Y 비행
  [영지 비행 장치](land_flying_device.md)의 비행
  [고양이 사료](../feature/cat_bowl.md)의 관전자 변경
  [고양이 사료](../feature/cat_bowl.md)의 자석으로 아이템 회수
  

---

## 활동
다음 행동은 활동도를 증가시킵니다:
- 엔티티 거래, 각각 +`100`
- 블록 파괴, 블록 설치, 블록 업데이트, 각각 +`40`
- 아이템 줍기, 아이템 버리기, 컨테이너 들기, 컨테이너에 넣기, 매번 +`20`
- 엔티티 대미지, 매번 +`10`
- [고양이 사료](../feature/cat_bowl.md) 플레이어가 있을 때, 매 초 +`4`
- 플레이어가 있을 때, 매 초 +`1`

각 영역의 활동성 한도는 `200,000`입니다. 영토 내에서 활동성이 매 `5,000`마다 +`1`의 [영토 에너지](land_energy.md)를 보존할 수 있습니다.
12개월마다 보존할 수 있는 [영토 에너지](land_energy.md) 포인트를 검사합니다. 전체 합계가 `20`% 미만인 경우 전체가 손상됩니다. 그렇지 않으면 다음이 발생합니다:
- 보존할 수 없는 [영토 에너지](land_energy.md)가 손상됩니다.
- 보존할 수 있는 [영토 에너지](land_energy.md)가 없으면 [영토 생성기](land_block.md)와 함께 모두 손상됩니다.

활성화된 영토 생성기가 가리키는 방향은 `0`~`999`%의 활동성을 나타냅니다.
공식= Min (`999`, trunc (`현재 총 활동성` / ((`현재 시간` * `마지막 검사 또는 생성 시간`) / `6개월`) / (`5000.0` * `현재 총 에너지 포인트`) * `100.0`))
보통 `100`%를 초과하면 안전하며 손상이 없습니다.
