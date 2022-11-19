---
title: "⛏️ 메모 - ROW 개발 기록"
date: 2022-11-09. 08:18
categories: ⛏️Memo
---

## 💎 ROW 개발 기록

---
> 개발 기록을 하기 시작한 시점을 기준으로, v1.0.0 부터 명칭한다.  
> 버전 업 기준은 [링크](https://okayoon.tistory.com/entry/%EA%B0%9C%EB%B0%9C-%EB%B2%84%EC%A0%84%ED%91%9C%EA%B8%B0-%EB%8C%80%EB%9E%B5%EC%A0%81%EC%9C%BC%EB%A1%9C-%EC%9D%B4%ED%95%B4%ED%95%98%EA%B8%B0)를 참고한다.  

## 💎 v1.0.1-Alpha

---
{% youtube "https://youtu.be/UdpJjhZ6WbI" %}
<br>

- 멀티 플레이 진행 시, 자신을 제외한 다른 플레이어의 회전값이 제대로 적용되지 않던 문제 수정

## 💎 v1.0.2-Alpha (최신)

---

- Menu Scene 에서 Lobby Panel 과 관련하여 발생하던 오류 로그 수정
- Lobby Panel 에서만 보여야하는 Team Panel 의 오브젝트 계층 구조 위치 수정
- Team Panel 을 갱신하지 않고 있던 문제 수정 (OnPlayerJoined, OnPlayerLeft)
- Team Panel 에 PlayerRef.PlayerId 가 적용되도록 수정 (임시, 닉네임으로 바꿔야 함)

- 추후 적용시키고자하는 SteamWork 와 관련하여, 유니티 프로젝트에 Steam SDK 임포트
- SteamWork 개발자 등록에 필요한 100$ 결제 (12만원..)

## 💎 앞으로의 마일스톤

---

- 동적으로 생성할 오브젝트 싱크 (몬스터, 공격 오브젝트, 아이템 오브젝트 등)  
- RPC, OnChanged 를 이용한 게임 이벤트 싱크 (텥레포트 이벤트 발생, 상자 열기 등)  
- 텔레포트 이벤트 및 보스, 다음 스테이지로의 이동  
- 인 게임에서 열 수 있는 Setting Panel  
- Lobby 에서 캐릭터 선택 및 인 게임 적용  
- 인 게임 UI (HP, Skill Cooldown 등)
- 인 게임 Result  
- 인 게임 채팅  
- Steam 연동? (인증 및 업적 관련, PlayFab)
- 몬스터 생성 알고리즘 (Risk Of Rain 2 의 감독 시스템 참고)
