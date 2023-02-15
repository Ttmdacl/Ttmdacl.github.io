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

### 💎 v1.0.7 (최신)

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

### 💎 앞으로의 마일스톤

---

- 텔레포트 이벤트, 다음 스테이지로의 이동  
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
- 보스 몬스터 움직임이 Y축으로 떨림  
  - NavMesh Agent 세팅 관련 문제로 예상됨  
