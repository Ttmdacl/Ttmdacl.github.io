---
title: "⛏️ ROW 개발 기록"
date: 2022-11-09. 08:18
categories: ⛏️Memo
---

### 💎 ROW 개발 기록

---
> 개발 기록을 하기 시작한 시점을 기준으로, v1.0.0 부터 명칭한다.  
> 버전 업 기준은 [링크](https://okayoon.tistory.com/entry/%EA%B0%9C%EB%B0%9C-%EB%B2%84%EC%A0%84%ED%91%9C%EA%B8%B0-%EB%8C%80%EB%9E%B5%EC%A0%81%EC%9C%BC%EB%A1%9C-%EC%9D%B4%ED%95%B4%ED%95%98%EA%B8%B0)를 참고한다.  
>> 23-02-15 그냥 내 좆대로 하기로 한다.

### 💎 v1.0.1

---
{% youtube "https://youtu.be/UdpJjhZ6WbI" %}
<br>

- 멀티 플레이 진행 시, 자신을 제외한 다른 플레이어의 회전값이 제대로 적용되지 않던 문제 수정

### 💎 v1.0.2

---

- Menu Scene 에서 Lobby Panel 과 관련하여 발생하던 오류 로그 수정
- Lobby Panel 에서만 보여야하는 Team Panel 의 오브젝트 계층 구조 위치 수정
- Team Panel 을 갱신하지 않고 있던 문제 수정 (OnPlayerJoined, OnPlayerLeft)
- Team Panel 에 PlayerRef.PlayerId 가 적용되도록 수정 (임시, 닉네임으로 바꿔야 함)

- 추후 적용시키고자하는 SteamWork 와 관련하여, 유니티 프로젝트에 Steam SDK 임포트
- SteamWork 개발자 등록에 필요한 100$ 결제 (12만원..)

### 💎 v1.0.7

---

- Built In에서 URP로 렌더링 파이프라인 변경
- FlatKit (Toon Shader) 에셋 적용
- 메인 메뉴 UI 개선
- 멀티 플레이 개선
  - 네트워크 Lobby에 접속한 상태일때만 플레이 시도할 수 있도록 조건 추가
  - 현재 네트워크 상태 디버깅 용 UI
  - 세션 생성 UI (UI만)
  - 모든 플레이어가 준비를 눌러야 시작 가능 (샘플 프로젝트에서 돚거)
  - 인게임
    - 채팅/로그
    - 인게임 UI
      - HP, EXP, Skill 등
      - ESC 눌렀을 때 뜨는 UI
        - Setting 버튼과 Setting UI (UI만)
        - Disconnect 버튼
    - StageManager
      - 몬스터, 상자, 제단, 텔레포터 생성 싱크
- 임시 스테이지 모델
- 임시 캐릭터 모델, 애니메이션

### 💎 v1.0.8 (최신)

---

- 보스 이벤트
- 보스 몬스터 움직임이 Y축으로 떨리던 문제 해결  
  - 몬스터들은 모두 NavMesh로 움직이는데,  
  - 보스 몬스터 프리팹의 RigidBody Freeze Position 이 체크 해제되어 있어서 계속 아래로 떨어지던 거였음  
- 보스 몬스터 UI (이름, 설명, 체력바)
- 다음 스테이지로의 이동  

### 💎 앞으로의 마일스톤

---

- 텔레포트 이벤트
- Lobby 캐릭터 선택 인 게임 적용  
- 인 게임 Result  
- Steam 연동? (인증 및 업적 관련, PlayFab)
- 몬스터 생성 알고리즘 (Risk Of Rain 2 의 감독 시스템 참고)
- 로딩
- 키 변경, 설정창

### 💎 인지된 버그, 수정사항

---

- 아이템 ID 로컬  
- Bullet 1 을 Client 가 쏘면 RPC가 작동하지 않음  
  - 왜지  
- 몬스터 오브젝트가 풀에서 다시 스폰되면 해당 몬스터의 HP Bar가 보이지 않음  
- 상자, 제단, 텔레포터 위치 싱크  
  - 현재 Network Transform 으로 땜빵되어 있음  
- 씬이 넘어가면 풀링 오브젝트들이 전부 Destroy 되어서 'MissingReferenceException: The object of type 'NetworkObject' has been destroyed but you are still trying to access it.' 에러 발생

---

움직임 미끄러지는 것 없이 -> 새로 만들어야 할 것 같은? NetworkTransform 으로 바꾸고 직접 계산 하는 느낌으로  
로딩  
땜빵으로 Network Transform 담 => 추후 대기 후 스폰 필요  
불릿1 클라이언트가 쏘면 데미지 없음  
아이템 ID 싱크  

디렉터  
어드레서블에셋  
업적 체커  
Result Recorder  
기획 / 모델링 / 이펙트 / 사운드-?  
캐릭터() - 몬스터 - 아이템 - 지역  
아이템 출현 / 아이템 정보, 아이템 인터렉트, 아이템 데이터 싱크, 아이템 소유  

TAB UI? 롤 탭 / 상태창 스탯  
몬스터 / 엘리트  
보스 연출  
제단들 상자들  
씬 하나로 통합??  
설정 - 그래픽/컨트롤 설정, 해상도 초기화  
데이터 저장 기준 Because 치터  
네이버 가능하다면..  
Or Steam 출시하지 않아도 된다면  
업데이트? 어드레서블 오브젝트?  
텔레포터? 꼭 찾아서 쓰는걸로?  
