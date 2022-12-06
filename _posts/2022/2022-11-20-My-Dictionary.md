---
title: "⛏️ 메모 - 내가 만드는 백과사전/정보모음"
date: 2022-11-20. 11:56
categories: ⛏️Memo
---

### 💎 [브루트 포스 탐색](https://en.wikipedia.org/wiki/Brute-force_search)  

---

-> 무지성 노가다 대입, 100% 정확성  

### 💎 그리디

---

### 💎 fetch (=bring)

---

- CPU가 명령을 수행하기 위해 그 명령어를 레지스터에서 꺼내 오는 것
- 위 말고도 그냥 일반적으로 가져온다는 뜻으로 많이 쓰이기도 하는 듯

### 💎 memory (메모리)

---

- 레지스터(CPU) - 캐시메모리 - 주기억장치 - (캐시메모리) - 보조기억장치
- 일반적으로 용량과 속도 반비례, 속도와 용량 대비 가격 비례

- 레지스터 데이터 읽기 = 머릿속에 있는 기억 떠올리기
- 주기억장치 데이터 읽기 = 책장에 꽂혀 있는 책에서 특정한 책을 찾아 내용을 읽는 행동
- 보조기억장치 데이터 읽기 = 지구를 한 바퀴 돌아서 특정한 내용 찾아오기

[메소드 스텁](https://ko.wikipedia.org/wiki/%EB%A9%94%EC%86%8C%EB%93%9C_%EC%8A%A4%ED%85%81)  

### 💎 register (레지스터)

---

- 프로세서에 위치한 고속 메모리
- 극히 소량의 데이터나 처리 중인 중간 결과와도 같은 프로세서가 바로 사용할 수 있는 데이터를 담고 있는 영역
- 컴퓨터 구조에 따라 크기와 종류가 다양

### 💎 MainBoard, MotherBoard, SystemBoard

---

- 다 똑같은 용어, 우리나라는 보통 메인보드라 칭하고, 해외에서는 마더보드라 칭하는 경우가 많음  

### 💎 -ware

---

- ~로 만들어진

- Hardware (H/W)
- 딱딱한 것으로 만들어진 (물리, 외적으로)
- 물리적으로 만들어진 컴퓨터 부품, 혹은 부품으로 조립된 전자 기기

- Firmware
- 내성을 가진것으로 만들어진? (내적으로)
- H/W에 각인된 고정된 Software, 전자 부품이 기본적으로 가지고 있는 Software
- ROM에 기록됨 (Read-only memory, 비휘발성)  

- Software
- 부드러운 것으로 만들어진 (하드웨어와 반대의 개념으로서)
- 만질 수 없는 가상의 프로그램

- Malware
- 악으로 만들어진
- 컴퓨터 바이러스, 해킹 관련하여

- Wetware?
- 젖은 것으로 만들어진 (= 뇌?)  

### 💎 Swizzling (= mix up)

---

- 휘몰아치는, 컴퓨터  용어로는 벡터의 구성 요로를 임의로 재정렬하고 결합하여 벡터를 구성하는 기능 (CG에서)

- Shader에서는  

- 그 외에도 Pointer Swizzling 이라는 것도 있음
- 포인터로 링크된 자료 구조 단위를, ID나 이름 등으로 대체함으로써 프로그램을 다시 시작하더라도 성공적으로 파일 데이터를 로드, 역직렬화 시키는 방법

- (마인크래프트의 휘몰아치는 칼날은 Sweeping)  

### 💎 #pragma

---

- 사전적 의미로 만능
- VS C++에서 컴파일러에게 그 뒤에 오는 내용을 따라 어떤 일을 하라는 전처리 명령어로 사용
- 컴파일러에게 직접 명령을 내리는 지시자  

### 💎 processor (프로세서)

---

- 처리기, 일반적으로 중앙처리장치 (CPU) = 명령어를 해석하는 컴퓨터의 한 부분
- 그래픽처리장치 (GPU) 도 컴퓨터의 일부이지만 단지 '프로세서' 라는 용어만 사용하였을 때 그래픽 처리 장치를 뜻하는 경우는 아직 많지 않음

- 마이크로 프로세서 > CPU

### 💎 instruction

---

- 명령, (사전 = 지침)  

### 💎 Interrupt (인터럽트)  

---

- CPU에서 프로그램을 실행하고 있을 때 입출력 하드웨어 등의 장치에 예외상황이 발생하여 처리가 필요할 경우에 CPU에게 알려 처리할 수 있도록 하는 것

- != Polling (폴링)
- 폴링은 하나의 장치 혹은 프로그램이 충돌 회피 또는 동기화 처리 등을 목적으로 다른 장치 혹은 프로그램의 상태를 주기적으로 검사하여 일정한 조건을 만족할 때 소우신 등의 자료처리를 하는 방식
- 인터럽트는 대상을 주기적으로 감시하여 상황이 발생하면 해당처리 루틴을 실행해 처리하는 폴링과는 달리, 상대가 CPU에게 일을 처리해 달라고 요청하는 수단

### 💎 CPU 명령어 사이클 (instruction cycle, 인스트럭션 사이클)

---

마이크로프로세서가 메모리로부터 프로그램 된 한 개의 기계어 명령어를 가져와 어떠한 동작을 요구하는지를 결정하고 명령어가 요구하는 동작을 수행하는 연속적인 동작 과정

= 즉, 명령어를 꺼내와 실행하기 위한 연속적인 동작 과정

-1. 사용되는 회로

- PC : 다음에 실행할 명령어에 대한 메모리 주소를 추적
- MAR : 다음에 실행할 명령어의 메모리에 있는 주소를 보관
- MBR : 메모리로부터 페치(fetch)되어 cpu가 처리할 준비가 된 데이터나 메모리에 저장되어 대기 중인 데이터를 보관하는 양방향 레지스터
- IR : 메모리로부터 fetch 되는 (현재 실행할) 명령어를 일시적으로 보관하는 영역
- CU : 명령어 인출, 해독, 실행을 위한 제어신호를 타이밍에 맞춰 발생시킨다.
- ALU : 산술 및 논리 연산을 수행

-2. 명령어 기본 사이클

- CPU에서 명령어를 읽어오는 단계

-2-1. 명령어 인출 사이클 (instruction fectch 사이클)

- CPu에서 명령어를 실행하는 단계

[참고](https://gamedevlog.tistory.com/71)

### 💎 오버플로우, 언더플로우  

---

오버플로우 : 변수가 표현할 수 있는 최대 범위 너머로  
언더플로우 : 변수가 표현할 수 있는 최소 범위 너머로  

### 💎 JSON

---

데이터 저장 방식  
Key <-> Value

### 💎 DB, DataBase

---

방정리를 왜 할까 : 잘 찾을려고! (잘 보관하려고가 아니라)  
데이터도 메모장으로 저장하는 것보다 찾을 때 천배 낫다  
제목 (문자열)로 찾는 것보다 분류로 찾는 게 빠르다  

No Index : 전부 다 뒤진다  
SQL : 정형화, 대기업, 실수를 절대로 하면 안될 때  
NoSQL : 비정형화, 앞으로 뭔가 많이 바뀔 때  

### 💎 BC, AD

---

BC : Before Chirst, 기원 전  
AD : Anno Domini nostri lesu Christi (라틴어), Anno Domini (라틴어 줄인), In The Year Of Our Load, Jesus Christ (영어), 기원 후  

### 💎 AM, PM

---

A.M. : Ante Meridiem, 오전  
P.M. : Post Meridiem, 오후  

### 💎 리토폴로지  

---

### 💎 휴먼 덴시티  

---

창틀 50  
전체 창 600 1800  
개별 창 50 50  
근데 이쁘게 하고 싶어서 20  
안열꺼면 깔끔해보이니까  

복도 1500 1800  
문 900 1800 / 2100  
원래 5천 해도 3천 쓰고 막그러는데  
천정고 3미타정도로  
일본 낮은 뭐시깽이하려면 2700 2400  

### 💎 키워드  

---

인하우스 툴  
튜플
에라토스테네스의 체  
Leading 0  
요세푸스 문제
Argument <> Parameter  
URI  
WebRequest  
gcc  
공변성과 반공변성  
in 제네릭 한정자  
in 매개변수 한정자  
커널  
시암의 방법  

System.Random Unity.Random 차이
format  
vendor  
다중 사용자 시스템, 단일 사용자 시스템  
모뎀  
company  
solution  
centor  
suite  
address  
data transfer  
전송 매체 Transmission Medium  
device  
Ethernet  
Traffic  
Internet Communication ?  
Cell Phone  
OSI  
멀티캐스트  
FFT 고속 푸리에 변환  
lower_bound, upper_bound
cin.fail  cin.eof  여러 줄 입력 끝 판단  
scanf printf 도 malloc 을 사용한다 >> 힙 할당이 생긴다  
C 메모리 구조  
C for문 안에서의 변수 선언 불가능 ? Cpp 컴파일러가 읽어서 가능? 
메모리 누수, 댕글링 포인터  
이 문제를 알아서 해결해주는 것이 GC  
문자열 리터럴 풀 = 전역변수가 저장되는 곳  
문자열 > 프로그램 내에서 어디든지 사용 가능 = 전역 변수  
메모리 접근 > OS  
왜 시작 위치만 저장하느냐> 문자열 자체가 끝에 \0 을 가지고 있기 때문
버퍼 입력버퍼 버퍼링  
주사 방식  
scanf 의 scan 주사  
HW  
관리 커널  
조게껍데기 셀  
커널 셀 ㅡ 운영체제  
사용자 프로그램  
유저 입력  
입력 명령 해석 셀  
셀에서 실행  
셀 명령러 해석기  
Bar Cmd Exe 확장자 차이  
단말기 = 터미널
맨 마지막, SW에 있어서 최종 소비자
SOP
snippet 
서드파티
pretty much (of)
너무 이른 최적화
전처리기 지시어
Reference Counting
STL Vector vs Array
순람표 룩업 테이블
C# default
Unity curve.Evaluate(
로렘 입숨(lorem ipsum;
### 💎 복사해서 쓸 것  

---

### 💎 단순 영단어

---

- abbreviation : 약어
- Meridiem (라틴어) : midday, 정오
- scammer : 사기꾼
- legit : 합법
- philanthropist : 자선가
- deposit : 위자료
- head out : 나가다
- jfc : 지서스 퍼킹 크라이스트
- autograph : 싸인, 자필
- ayt : Are You There
despite
imprecisions  
RTFM  
get rid 제거하다  
violation 위반  
predicate  
approach 학문이나 연구 등에서, 대상에 접근하는 일  
wears out 닳다
last indefinitely 무기한 지속
troubleShooting 문제해결
straightforward 똑바로
indicate 나타내다 =? 지시자
superfluous 불필요한
biography
determine
toc
narrow
reasonable  
arbitary  
subsequence  
adjacent  
nive  
intuitive
calibration
agile
parse
sudo
assuming

### 🎲 곱셈이 나눗셈보다 빠르다

---

- 곱셈은 한 번에 처리
- 나눗셈은 뺄셈을 계속해서 처리

[참고](https://blog.naver.com/PostView.nhn?blogId=fah204&logNo=221573584390)

### 🎲 서버 컴퓨터는 대부분 리눅스

---

리눅스 -> 오픈소스 -> 여러 대 사용해도 비용 X -> 서버 컴퓨터는 대부분 리눅스

### 🎲 서버도 그냥 컴퓨터다

---

서버 컴퓨터마다 모니터, 키보드, 마우스 하나하나 껴서 업데이트  
서버 터지면(= 꺼지면) 다시 키고 프로그램 열고 함  

규모가 커질수록 구조를 다 알 수 없음 + 컴퓨터를 다 쓸 수 없음  
-> 클라우드 서비스

### 🎲 서버 API

---

은행 창구 == API  
클라이언트 개발자하고 미리 한 약속, 다 외울 수 없음 -> API 명세서

http://우리은행용산지점/입출금창구?신분증=주민등록번호
서버위치/API주소?가져가기로한데이터

API 하나만 따주세요 -> 새로운 기능/창구를 하나 만들어주세요  
API 개발은 끝났는데 클라이언트는 아직 -> 창구는 만들었는데 요청하는 쪽이 아직  

Open API : 누구나 요청할 수 있게 열린 API, i.e. 공공데이터 포털  

### 🎲 블렌더 모음

---

3D 커서 원위치 : Shift + C  
솔리드/와이어 토글 : Shift + Z, 그냥 Z 꾹
스냅 토클 : Shift + Tab  
Join : 재료템 먼저 선택, 무기 나중에 선택  
재계산 : Alt + N  
Alt 마우스방향말고, ~ 누르면 쉬움
와이어프레임 만들고 솔리디 파이 하면 벽 틀?

[메쉬 부드럽게](https://longtime0423.postype.com/post/10045292)
  
[Favela/Slum 블렌더](https://barell4.gumroad.com/l/favelagenerator?recommended_by=search&_ga=2.134772723.349083529.1661141255-339463231.1661141255&_gl=1*dqamgw*_ga*MzM5NDYzMjMxLjE2NjExNDEyNTU.*_ga_6LJN6D94N6*MTY2MTI0ODkzOC4xMC4xLjE2NjEyNDkyNzAuMC4wLjA)

### 🎲 채용 공고 키워드 모음

---

rss
텐서플로우
STL  
멀티스레드  
R&D  
DirectX 렌더링 파이프라인  
모던 C++  
Go  
데이터 정제/분석/시각화 (R, Python)  
데이터 플랫폼 (Mysql, Spark, Presto)  
머신러닝  
해킹 대응 및 보안 이슈  
Andtoid IOS  
Win32 API, MFC  
서버 아키텍쳐  
서버 성능 튜닝  
DB Scheme  
Windows/Linux Programming  
모듈 서버  
boost/tbb 라이브러리  
SQL/Nosql  
진취적  
소켓 프로그래밍, 코드 최적화, DB  
라이브 서비스  
서버 엔진 개발  
Network 라이브러리 개발  
Boost 라이브러리  
C++14 17 20 등 새로운 피처에 관심이  
애자일회고  
Boost Asio  
DB (Redis)  
디버깅 , 이슈 추적  
분산 네트워크 환경에서 발생하는 OS, Network, DB 문제  
라이브 서비스 중에 대규모 코드 리팩토링 및 최적화  
그래픽 생산성, 퀄리티 개선을 위한 툴 개발  
상용 툴 커스터 마이즈  
그래픽 관련 엔진 코드 분석/수정을 통한 성능 최적화 전반  
통상적인 엔진 그래픽 관련 버그 수정 및 업그레이드  
nodejs / Python  
TypeScript React Vue  
대량의 데이터  
수상 경력  
UI UX  
분산 프로세스, 멀티 스레드 기반 로직  
도메인  
코드 보안 또는 저수준 언어에 대한 이해  
어셈블리 분석, 해킹툴 제작  
머신러닝 모델을 실제 프로덕션 환경에 적용  
머신러닝을 위한 솔루션 프로토타이핑  
강화학습  
캐글  
다양한 플랫폼에 대한 각 최적화  
렌더링 기술  
미들웨어 통합, 최적화  
Graphics API (DX11/12 OpenGL Vullkan)  
AWS  
DDV  
시스템 튜닝 및 쿼리 튜닝  
마이그레이션 및 백업 관리  
모니터링 및 트러블 슈팅  
DV 개발 가이드  
MariaDB  
운영 자동화 스크립트 PowerShell Shel Pythom  
MongoDB Redis  
Backend API 및 서버  
Backend System Architecture  
.NET  
RDBMS (MSSQl, MySQL)  
PHP  
Ajax  
O2O  
JIRA  
CI/CD  

### 🎲 동기 비동기 예시  

---

병원들어갔어 접수처에서 순서기다리세요 부를게요~ 하는거랑  
들어가자마자 아무것도 안하고 기다리는 것 차이  

페이지에서 조금씩조금씩 나오는 거  

### 🎲 Setter 쓰지 마라, 의미있는 메소드를 만들어라  

---

### 🎲 이건 할 줄 알아야 한다  

---

<https://en.wikipedia.org/wiki/XOR_swap_algorithm>
버블 정렬
퀵 정렬 어떻게 도는구나 정도
나머지 정렬 그냥 있었구나 오케이
radix sort
해쉬 맵 링크드 리스트 트리=바이너리 서치=순서대로 출력 이건 할 줄 알아야

### 🎲 .NET 프레임워크 Old vs .NET Core New  

---

코어는 윈도우 리눅수 맥 모두 실행가능  
거의 똑같음  

### 🎲 Int 크기  

---

옛날에는 2바이트 16비트 체ㅔㅈ여서  
지그은 4바이트 32비트  
64비트 더 많이 쓰는데? 혼용해서  
언젠가 8바이트 ?  

### 🎲 주소 크기  

---

VS (SW) 가 32Bit 라 주소 크기가 4Byte = 32bit  
OS는 64bit 인데  

### 🎲 Placement New 기법  

---

정적 메모리 풀을 만들어 놓고 할당 받아 쓰는 방식  
대규모 탄막이나 파티클이 등장할 경우 프레임 드랍을 막기 위해  

### 🎲 C# List  

---

크기 기본값을 설정해주지 않으면 다 채울 때 까지 재할당(+복사) 하지 않음  
아니라면 2배씩  
StringBuilder Queue Stack 도 마찬가지  
기본 4개의 용량을 가지고 있음  

초기 사이즈가 예측 불가능하거나 Add Remove가 빈번하면 Linked List 추천  
List 요소 지우면 뒤에 있는 요소 한칸 땡겨서 모두 다시 복사  

### 🎲 C++ time  

---

```cpp
#define _CRT_SECURE_NO_WARNINGS
#include <iostream>
#include <time.h>
using namespace std;
int main()
{
    time_t cur;
    time(&cur);
    tm* gmTM = gmtime(&cur);
    printf("%d\n%02d\n%02d", 1900 + gmTM->tm_year, gmTM->tm_mon + 1, gmTM->tm_mday);
}
```

### 🎲 무지성 복사  

---

<https://gall.dcinside.com/mgallery/board/view/?id=game_dev&no=89582&exception_mode=recommend&page=1>  

https://likejirak.tistory.com/182  
https://stackoverflow.com/questions/33090193/linguistic-meaning-of-let-variable-in-programming
https://stackoverflow.com/questions/1714515/how-can-i-pad-an-int-with-leading-zeros-when-using-cout-operator
http://daplus.net/github-github-markdown-%ED%85%8C%EC%9D%B4%EB%B8%94%EC%97%90-%EC%B2%B4%ED%81%AC-%EB%B0%95%EC%8A%A4-%EB%98%90%EB%8A%94-%EB%88%88%EA%B8%88-%ED%91%9C%EC%8B%9C%EB%A5%BC-%EA%B7%B8%EB%A6%AC%EB%8A%94/
https://ko.wikipedia.org/wiki/%EC%9C%84%ED%82%A4%EB%B0%B1%EA%B3%BC:TeX_%EB%AC%B8%EB%B2%95
https://namu.wiki/w/%EC%88%98%ED%95%99/%EC%95%BD%EC%96%B4%20%EB%B0%8F%20%EA%B8%B0%ED%98%B8
https://ko.wikipedia.org/wiki/%EB%85%BC%EB%A6%AC_%EA%B8%B0%ED%98%B8
https://zetawiki.com/wiki/%EC%9E%90%EC%97%B0%EC%88%98%EC%A7%91%ED%95%A9,_%EC%A0%95%EC%88%98%EC%A7%91%ED%95%A9,_%EC%9C%A0%EB%A6%AC%EC%88%98%EC%A7%91%ED%95%A9,_%EC%8B%A4%EC%88%98%EC%A7%91%ED%95%A9,_%EB%B3%B5%EC%86%8C%EC%88%98%EC%A7%91%ED%95%A9
https://shoark7.github.io/
https://poalim.tistory.com/37
https://namu.wiki/w/%EC%9C%84%EC%83%81%20%EA%B3%B5%EA%B0%84
https://namu.wiki/w/%EC%9D%B4%EC%82%B0%EC%88%98%ED%95%99#s-3
https://namu.wiki/w/2%EC%B0%A8%20%EC%9E%89%EC%97%AC
https://namu.wiki/w/%ED%95%A9%EB%8F%99%EC%8B%9D
https://ko.wikipedia.org/wiki/%ED%8F%B4%EB%A7%81_(%EC%BB%B4%ED%93%A8%ED%84%B0_%EA%B3%BC%ED%95%99)
https://ko.wikipedia.org/wiki/%EC%9D%B8%ED%84%B0%EB%9F%BD%ED%8A%B8_%ED%95%B8%EB%93%A4%EB%9F%AC
https://ko.wikipedia.org/wiki/%EB%AA%85%EB%A0%B9_%EB%A0%88%EC%A7%80%EC%8A%A4%ED%84%B0
https://feralresearch.org/lab/api-calls-from-inside-vrc/
https://ask.vrchat.com/t/http-requests/1803
https://github.com/Roliga/udon-video-decoder
https://gitlab.com/anfaux/pixel-proxy/-/blob/main/server-node/modules/encode.js
https://vrchat.com/home/launch?worldId=wrld_7508e408-ba6a-4478-b772-6af430c89286&instanceId=51500~private(usr_74fd4823-008f-4434-969c-c892e7c143e2)~region(eu)~nonce(031b2879-124f-4943-b075-2700f61ee200)
https://gall.dcinside.com/mgallery/board/view/?id=celeste&no=1177
https://riskofrain2.fandom.com/wiki/Directors#Spawn_loop
https://github.com/desktop/desktop/issues/14936

[게임 시스템 디자인 시작하기](https://www.slideshare.net/ByungChun2/ss-140743429)
[좋은 git commit 메시지를 위한 영어 사전](https://blog.ull.im/engineering/2019/03/10/logs-on-git.html)
[메모리구조에서의 자료구조](https://daeun28.github.io/%EC%BB%B4%ED%93%A8%ED%84%B0%EA%B3%B5%ED%95%99-%EC%8A%A4%ED%84%B0%EB%94%94/post17/)
[지역변수 전역변수 접근/속도차이](https://www.acmicpc.net/board/view/905)
[Bool 변수 이름 제대로 짓기 위한 최소한의 영어 문법](https://soojin.ro/blog/naming-boolean-variables)
[C# 메모리 관리](https://blog.naver.com/njuhb/140165599614)
[C# 프로퍼티는 Ref 로 못전달한다, 프로퍼티 구조](https://dh-0501.tistory.com/138)
[C 가변 길이 배열](https://jungpaeng.tistory.com/89)
[C 가변 길이 배열](http://m.todayhumor.co.kr/view.php?table=total&no=9553647)
[C 가변 길이 배열 - 백준(컴파일러)](https://www.acmicpc.net/board/view/47218)
[C 가별 길이 배열 - 컴파일러](https://seolin.tistory.com/67)
[C 헤더 파일이 없어도 실행이 되는 이유](https://yoostudy.tistory.com/entry/%ED%97%A4%EB%8D%94%ED%8C%8C%EC%9D%BC-%EC%97%86%EC%96%B4%EB%8F%84-%EC%8B%A4%ED%96%89-%EB%90%98%EB%8A%94-%EC%9D%B4%EC%9C%A0)
[C 동적할당](https://security-nanglam.tistory.com/78?category=800096)
[C 포인터 크기](https://security-nanglam.tistory.com/66)
[포인터, 사용하는 이유](https://oper6210.tistory.com/m/160)
[유니티 Vector3 Equals](https://docs.unity3d.com/ScriptReference/Vector3.Equals.html)
[유니티 Vector3는 스택에 생성된다 = 값 형식이다 = Struct](https://3dmpengines.tistory.com/1566)
[유니티 Vector3 Struct](https://answers.unity.com/questions/1033383/code-performance-when-to-use-new-on-vector3.html)
[C# new Struct](https://asta8080.tistory.com/5)
[유니티 메모리 관리의 이해](https://smilejsu.tistory.com/560)
[float 연산이 정확하지 않다면 컴퓨터 계산기는 어떻게 소수를 계산하는가](https://www.quora.com/If-computers-cannot-compute-floating-numbers-accurately-how-do-calculators-and-scientific-computers-function)
[bool은 왜 1비트가 아니라 1바이트인가](https://zepeh.tistory.com/419)
[bool은 왜 1비트가 아니라 1바이트인가](https://stackoverflow.com/questions/2064550/c-why-bool-is-8-bits-long)
[1바이트는 왜 8 비트인가](https://zepeh.tistory.com/313)
[누적합](https://book.acmicpc.net/algorithm/prefix-sum)
[GetInstanceID 와 GetHashCode](https://daebalstudio.tistory.com/entry/GetInstanceID-%EC%99%80-GetHashCode-%EC%A0%95%EB%A6%AC%ED%95%A0-%EA%B2%83)
[유니티 프리팹 썸네일 안보임](https://forum.unity.com/threads/why-are-my-prefab-and-model-previews-not-showing.709544/)
[유니티 프리팹 썸네일 안보임](https://issuetracker.unity3d.com/issues/urp-prefab-preview-is-blank-when-a-custom-forward-renderer-data-and-default-layer-mask-is-mixed-are-used)
[유니티 강좌 여러가지](http://www.devkorea.co.kr/bbs/board.php?bo_table=m03_lecture&sca=&sfl=mb_id,1&stx=nodvicdk)
[쿠키런 사운드, 미들웨어, FMOD](https://v.daum.net/v/5ae023f36a8e510001f88d05)
[유니티, 프로젝트가 커질 때 코드 설계](https://unity.com/kr/how-to/how-architect-code-your-project-scales)
[컴공 자료](https://github.com/Prev/CSE-Summary)
[Untiy Inspector 에서 List Element 이름 바꾸기](https://forum.unity.com/threads/how-to-change-the-name-of-list-elements-in-the-inspector.448910/)
[Untiy Inspector 에서 List Element 이름 바꾸기](https://dev-youngil.tistory.com/1)
[Untiy Inspector 에서 List Element 이름 바꾸기](https://liveupdate.tistory.com/347)
<https://blogofth-lee.tistory.com/281>
<https://blog.popekim.com/ko/2012/01/11/compile-time-hash-string-generation.html>
<https://m.cafe.naver.com/ca-fe/web/cafes/26377973/articles/122961>
<https://moguwai.tistory.com/entry/C%EA%B3%BC-C%EC%9D%98-%EB%AC%B8%EB%B2%95%EC%A0%81%EC%9D%B8-%EC%B0%A8%EC%9D%B4%EC%A0%90>
<https://wikidocs.net/>
<https://blog.ab180.co/posts/open-graph-as-a-website-preview>
<https://velog.io/@jch9537/URI-URL>

### 기술 정보
<https://helpx.adobe.com/kr/photoshop/using/saving-selections-alpha-channel-masks.html>
<https://blog.naver.com/kids1412/222686829072>

### 코테
<https://www.slideshare.net/SuhyunPark23/kucc-2022-4>
<https://suyeoniii.tistory.com/13>
<https://gamedevlog.tistory.com/6?category=892157>
<https://baactree.tistory.com/14>
<https://pangtrue.tistory.com/305>
<https://pangtrue.tistory.com/303?category=724827>
<https://pangtrue.tistory.com/331?category=724827>
<https://namu.wiki/w/%EB%8F%99%EC%A0%81%20%EA%B3%84%ED%9A%8D%EB%B2%95>
<https://namu.wiki/w/%EB%A9%94%EB%AA%A8%EC%9D%B4%EC%A0%9C%EC%9D%B4%EC%85%98>
<https://stonejjun.tistory.com/23>

### 개인 프로젝트 참고
<https://kimkitty.net/archives/1638>
<https://stackoverflow.com/questions/26167387/run-git-commands-from-a-c-sharp-function>
<https://medium.com/@cuilongchang/unity-tricks-how-to-hide-a-ui-object-behind-a-transparent-ui-2700c12372c1>
[게임제작에 사용되는 영어단어](https://m.blog.naver.com/PostView.nhn?blogId=nicecapj&logNo=130062005836&proxyReferer=https:%2F%2Fwww.google.com%2F)
<https://gall.dcinside.com/mgallery/board/view/?id=game_dev&no=11872&list_num=30&search_pos=-15520&s_type=search_subject_memo&s_keyword=%EB%8D%98%EA%B7%B8%EB%A6%AC%EB%93%9C&page=2>
<https://gall.dcinside.com/mgallery/board/view/?id=game_dev&no=12015&list_num=30&search_pos=-15520&s_type=search_subject_memo&s_keyword=%EB%8D%98%EA%B7%B8%EB%A6%AC%EB%93%9C&page=2>
<https://gall.dcinside.com/mgallery/board/view/?id=game_dev&no=13690&list_num=30&search_pos=-15520&s_type=search_subject_memo&s_keyword=%EB%8D%98%EA%B7%B8%EB%A6%AC%EB%93%9C&page=2>
<https://gall.dcinside.com/mgallery/board/view/?id=game_dev&no=14783>
<https://gall.dcinside.com/mgallery/board/view/?id=game_dev&no=13710&list_num=30&search_pos=-15520&s_type=search_subject_memo&s_keyword=%EB%8D%98%EA%B7%B8%EB%A6%AC%EB%93%9C&page=2>
<https://gall.dcinside.com/mgallery/board/view/?id=game_dev&no=12155&list_num=30&search_pos=-15520&s_type=search_subject_memo&s_keyword=%EB%8D%98%EA%B7%B8%EB%A6%AC%EB%93%9C&page=2>

<http://wookje.dance/>
<https://career.nexon.com/common/main>
<https://unity.com/kr/how-to/tips-optimize-your-visual-studio-tools-when-coding-unity>
<http://waifubartending.com/>
<https://hits.seeyoufarm.com/>
<https://www.inven.co.kr/board/maple/2299/6421191>
<https://m.blog.naver.com/PostView.naver?isHttpsRedirect=true&blogId=rhukjin&logNo=222052759608>
<https://enlqn1010.tistory.com/9>
<https://www.inven.co.kr/board/maple/2304/9801>
<https://afsdzvcx123.tistory.com/entry/C-%EB%AC%B8%EB%B2%95-C-Linq-Take-Skip-%EC%9D%B4%EC%9A%A9%ED%95%98%EC%97%AC-%ED%95%84%EC%9A%94%ED%95%9C-%EA%B5%AC%EC%97%AD-%EC%9E%98%EB%9D%BC%EB%82%B4%EA%B8%B0>
[c# parse convert 차이](https://2-nan.tistory.com/43)
<http://1st.gamecodi.com/board/zboard.php?id=GAMECODI_Talkdev&no=1461>
<https://www.csharpstudy.com/CS6/CSharp-using-static-member.aspx>
<https://stackoverflow.com/questions/63178546/change-line-renderer-alpha-unity>
<https://www.gamejob.co.kr/Recruit/joblist?menucode=duty&duty=1>
<https://helenstudy.tistory.com/51>
<https://funfunhanblog.tistory.com/313>
<https://twitchemotes.com/channels/49045679>
<https://www.bensound.com/royalty-free-music/track/memories>
<https://m.blog.naver.com/PostView.naver?isHttpsRedirect=true&blogId=riomedevon&logNo=110106228406>
<https://pokemon.fandom.com/ko/wiki/%EB%B9%8C%EB%A6%AC%EC%A7%80_%EB%B8%8C%EB%A6%AC%EC%A7%80>
<https://namu.wiki/w/%EB%B9%8C%EB%A6%AC%EC%A7%80%EB%B8%8C%EB%A6%AC%EC%A7%80>
<https://unity.com/how-to/unity-ui-optimization-tips>
<https://m.blog.naver.com/PostView.naver?isHttpsRedirect=true&blogId=dus531400&logNo=140209199573>
<https://gall.dcinside.com/mgallery/board/view/?id=aoegame&no=16490887>
<https://www.dogdrip.net/195354145>
<https://twitter.com/DodgeRollGames/status/593625936131653632>
<https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life>
<https://blog.maplestory.nexon.com/>
<https://fuzzysound.github.io/jekyll-liquid>
[![Convertio](https://static.convertio.co/img/apple-touch-icon-76x76-precomposed.png)](https://convertio.co/kr/ "Convertio")
<https://learn.jettelly.com/unity-shader-bible/#buy-now>  
<https://www.pinterest.co.kr/>
<https://kitbash3d.com/>
<https://www.mixamo.com/#/>
<https://noonnu.cc/index>
<https://pixabay.com/>
<https://www.inflearn.com/my-courses>
<https://3dwarehouse.sketchup.com/>
<https://yogalayout.com/>
<https://www.artstation.com/huniartist>
<http://waifu2x.udp.jp/index.ko.html>
<https://easings.net/>
<https://www.dimensions.com/>
<https://hashcode.co.kr/code_runners>
<https://www.toptal.com/designers/colorfilter>
<https://www.toptal.com/developers/gitignore>
<https://color.adobe.com/ko/create/color-wheel>
<https://123apps.com/ko/>
<https://tumblbug.com/>
<https://johngrib.github.io/wiki/special-chars/?utm_campaign=asb&utm_medium=blog&utm_source=awesome-blogs.petabytes.org>
<https://discohook.org/>
<https://lospec.com/palette-list>
<https://www.fontspace.com/>
<https://www.zapsplat.com/>
<https://www.desmos.com/calculator?lang=ko>
<http://3dapi.com/>
<https://polyhaven.com/>
<https://rusalgames.tistory.com/>
<https://ambientcg.com/>
<https://cpetry.github.io/NormalMap-Online/>
<https://www.textures.com/>
<https://sketchfab.com/feed>
<https://3dsky.org/>
<https://www.cgtrader.com/>
<https://kenney.nl/>
<https://soundimage.org/>
<https://opengameart.org/>
<https://realfavicongenerator.net/>
<https://jekyllrb.com/docs/front-matter/>
<https://ansohxxn.github.io/blog/category/>
### 색
<https://cssgradient.io/>
### 소리
<https://dova-s.jp/>
<https://soundeffect-lab.info/>
<https://99sounds.org/>
<https://soundbible.com/>
<https://freesound.org/>
<https://www.freesfx.co.uk/>
<https://www.soundjay.com/>
<https://docs.google.com/spreadsheets/d/1GtehmgtnAX2dt5xM8Qv4Kj8-eZtGA5sRuCjw40oLI3o/edit#gid=0>
<https://sonniss.com/>
<http://sonniss.com/gameaudiogdc#1605031061361-34588c70-73f2>
<https://www.playonloop.com/>
### 이미지
<https://simpleicons.org/>
<https://icooon-mono.com/>

### 🎲 무지성 복사 2  

---

미나렛  
“Unfortunately this was not humanly possible”
music plays
“Until”
아킬레스 거북이  
사실관계적시  
b2b  
엠비? 엠바고  
백일하  
화투 배경에 메이드
엘리베이터 문을 열었는데 엘리베이터가 나온다
날씨도장
땅버섯
검은 합창단  
흰색 빨간색, 신 붉은 창  
우두머리 머리 하얀 손 마름  
아이 머리 하얀 손  
신 HW 우두머리 SW  
샤프트 각도
가시 선인장  
초야
파타모르가나  
태양 기둥  
고전  
/ 프리랜서의 핵심은 자유인데 오히려 반대  
자유는 무한 책임, 무한 책임은 불안, 불안은 필요 이상의 자기 통제  
그럼에도 불구하고, 완벽한 외적 자유를 가지고 산다는 느낌 자체가 좋다  
학창 시절에 선생님 수업 무시하고 내 방식대로 공부하는 느낌과 비슷하다.  
/ 불안이든 외로움이든 자기 통제의 강박이든 일정 수준을 넘으면 스트레스가 되고  
스트레스는 '반드시' 신체 건강에 영향을 준다고 생각  
길게 보시고 롱런하시길 바라렉요. 다른 말로 건강 챙기면서 하시라는 말이에요  
/ 뽀모도로 기법  
aa ASCII ART
공감주의  
/ 코드가 더러워도 좋으니 일단 완성을 해라,  
코드 퀄리티는 완성보다 우선시되면 안된다  
/ 개발 실력을 생각하면 자괴감만 들게 되어있다  
생각해야할 것은 내 개발 실력이 아니라 해결해야한ㄴ 문제  
문제 해결책에 집중할 때 비로서 엉뚱한 우울감에 빠지지 않은  
/ 공부는 정통으로  
하지만 구현은 꼭 정통일 필요는 없음  
/ 부전나비  
/ 동물이나 사람의 행동을 생물학적-진화론적으로 분석해보는 습관이 있다. 물론 그런 분야에 관해 전문적인 지식을 가지고 있거나, 제대로 공부해본 것은 아니지만, 나름의 논리대로 상식선에서 분석해보는 것이다. 예를 들어, 우리는 왜 어두운 곳을 두려워 할까? 우리는 왜 높은 곳을 두려워 할까? 같은 질문을 나름대로 분석해보자면 다음과 같다. 지금처럼 밤만 되면 환하게 세상을 비추는 가로등이나 언제 어디서든 빛을 낼 수 있는 손전등은 저 먼 옛날에는 존재하지 않았고, 때문에 어두운 밤이나, 깊은 동굴은 야생 동물에게 공격당할 위험성이 있었을 것이다. 때문에 어두움을 두려워하지 않은 인류는 살아남기 힘들었고, 반대로 어두움을 두려워한 인류는 상대적으로 살아남을 가능성이 높았다. 높은 곳을 두려워하는 이유도 앞의 이유와 비슷하다. 이런 식으로 내가 가지고 있는 상식 선에서 동물이나 사람의 행동, 본능을 분석하는 것이다. 하지만 어릴 때부터 풀리지 않는 의문이 하나 있다. 과연 사랑이란 무엇일까? 이 질문은 도저히 내 상식 선에서 대답할 수 없었다. 일반적으로, 사랑하게 되는 주된 이유는 외모다. 그런데 외모가 생존에게 주는 이점이 있다고 볼 수 있을까? -> 사회적 동물
i love egg
비바리움  
<https://blog.naver.com/shalacho/222114284512>
[문서로 먼저 적어라](https://twitter.com/DungeonKim/status/1136504723173863424)
[UI](https://imgur.io/gallery/XOT47)
["](https://blog.naver.com/blancleo/220606789517)
[수학 시각화](https://gall.dcinside.com/mgallery/board/view/?id=singlebungle1472&no=288516&exception_mode=recommend&page=1)
[목적은 수단이다](https://gall.dcinside.com/mgallery/board/view/?id=aoegame&no=18763369)
[기술 업계의 독성 말투](https://edykim.com/ko/post/tech-has-a-toxic-tone-problem-lets-fix-it/)
[IGN 인터뷰, 게임을 만들 때 가장 어려운 것은... 모든 것이다](https://kr.ign.com/control/11198/feature/geimeul-mandeul-ddae-gajang-eoryeoun-geoseun-modeun-geosida)
[Craftdaily, UI가 이쁘다!](https://thecraftdaily.com/ko-kr/)
[거리 풍경](https://www.instagram.com/reel/CcShiclj6Gw/?igshid=MDJmNzVkMjY%3D)
[롤 아트북](https://artbook.na.leagueoflegends.com/en_US/volume-one#)
[회전하는 아스키코드 도넛](https://donut.surge.sh/)
[VRChat 공연하시는 아티스트](http://meme-x.jp/)
[모션테이블](http://foxcodex.html.xdomain.jp/)
[바이트 비트 Beat](https://games.greggman.com/game/html5-bytebeat/)

### 🎲 무지성 복사 3  

---

[머테리얼 비교](https://answers.unity.com/questions/175695/comparing-materials.html)  
[머테리얼 인스턴싱](https://wergia.tistory.com/328)  
디더링  
유니티 스크린 이펙트 쉐이더  
베이커리 베이크 시 흰색 검은색 빨간색 초록색 파란색 얼룩
Auto-Atlasing . Texels per unit 40 ~ 80
글로벌 일루미네이션 . samples
보통 UV 오버랩 문제 > Texels per unit 값 올려주거나, UV 맵 자체 간격  
스텔실 쉐이더 
Mesh Baker
Force Power-Of-Two Atlas 체크 > 검은 공간 많은 텍스쳐를 크기 줄여줌  
HLSL (High Level Shading Language)
- 가장 유명하고 보편적으로 넓게 쓰임
GLSL (OpenGL Shading Language)
- OpenGL에서 사용하는 언어
CG (C for Graphics)
- 엔비디아가 마이크로소프트와 협력하여 만든 언어
[오후 3:49]카모뜨린: 프로그래밍 언어처럼 하나만 잘 배워두면 나머지는 쉽게 터득할 수 있다
[오후 3:50]카모뜨린: 유니티는 CG 언어를 사용, URP 부터는 HLSL 사용 (언리얼도 HLSL)
유니티는 추가적으로 언어를 제작 지원
Shader Lab
- 호환성은 가장 높지만, 그만큼 할 수 있는 게 제한적
Surface Shader
- 가장 쉽고 멀티 플랫폼에서 잘 대응되는 셰이더, 프로그래머가 아니더라도 배우기 쉬운 개념
- 아티스트 레벨에서 배우는
-> Shader Lab 이라는 스크립트 안에 CG 코드가 들어가 있는 형식
- 이걸 배워두면 Vertax & Fragment Shader 도 이해할 수 있고, 랜더 몽키로도 갈 수 있고, 노드로도 갈 수 있다
Vertax & Fragment Shader
- Surface Shader의 상위 버전, CG를 더 디테일하게 다룸
- Surface Shader가 오토 모드라면. Vertax & Fragment Shader는 수동이라는 느낌 
[CatLikeCoding](https://catlikecoding.com/)  
[Graph 그리기, Position에 따른 Color](https://catlikecoding.com/unity/tutorials/basics/building-a-graph/)  
[수학적 Coordinate, Color](https://catlikecoding.com/unity/tutorials/basics/mathematical-surfaces/)  
: Mesh Colluder 끼리 충돌 안함, Convex 쓰면 댐  
[Surface Shader (눈)](https://blog.naver.com/PostView.naver?blogId=plasticbag0&logNo=221439156276&parentCategoryNo=&categoryNo=45&viewDate=&isShowPopularPosts=false&from=postView)  
[Scene에서 빛 모두 없애기](https://learnandcreate.tistory.com/m/115)
sssShader  
[오라](https://blog.naver.com/cra2yboy/222219692268)

### 프로그래밍

---

<https://www.curioustore.com/#!/>

<https://progl.tistory.com/5>

<https://blog.kimtae.xyz/7>

<https://sungjjinkang.github.io/c++/2021/01/28/tiny_optimization.html>

<https://moaimoai.tistory.com/311>

<https://thebook.io/080201/>

<https://www.sysnet.pe.kr/2/0/11805?pageno=0>

<https://jeong-f.tistory.com/96>

<https://developer-talk.tistory.com/220>
