---
title: "URL의 프로토콜 식별자 (Protocol Identifier)"
date: 2022-11-18. 10:42
categories: Programming Programming-Normal
---

일반적인 Web URL을 보면  
:// 앞에 https 가 있는 것을 볼 수 있다.  

:// 앞은 프로토콜 식별자 (Protocol Identifier) 로 사용되는 공간으로,  
여기에 적힌 프로토콜로 통신을 하겠다는 의미이다.  

그래서 여기에 https 가 적혀있으면 https 프로토콜로 통신을 하겠다는 의미  
다른 프로토콜이 적혀 있으면, https가 아니라 다른 프로토콜로 통신을 하겠다는 의미다  

다른 프로토콜을 사용하는 예시 하나로, VRChat 월드에서 사용되는 영상 스트리밍 서비스인 TOPAZ 가 지원하는 스트리밍 송출/송신 링크를 보게 되면,  

rtmp://topaz.chat/live  
rtspt://topaz.chat/live/StreamKey  

이런식으로 프로토콜 식별자에 rtmp와 rtspt가 적힌 걸 볼 수 있는데,  

이는 TOPAZ가 RealTimeMessagingProtocol인 rtmp, RealTimeStreamingProtocolTCP 인 rtspt,  
두 프로토콜을 이용해 통신을 하고 있다는 것을 알려준다.  
