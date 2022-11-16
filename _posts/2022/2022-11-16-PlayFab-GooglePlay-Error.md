---
title: "PlayFab, Google Play 연동 과정 중 에러 발생 시"
date: 2022-11-16. 11:38
categories: DayStone
---

## 문제

PlayFab과 Google Play 로그인 연동을 위한 코드 작성 중,

PlayGamesClientConfiguration 과,  
PlayGamesPlatform.Instance.Authenticate(); 에서 에러 발생

[참고 링크 1](https://github.com/playgameservices/play-games-plugin-for-unity/issues/3141)

[참고 링크 2](https://community.playfab.com/questions/61120/googleoauthnoidtokenincludedinresponse-when-loggin.html)

---

## 해결방법

22/11/16 기준, 아직까지 해결되지 않은 것으로 확인  
0.11.1 버전이라면, 0.10.14 버전으로 다운그레이드하여 사용 (참고 링크 2, PlayFab 답변 참고)  
