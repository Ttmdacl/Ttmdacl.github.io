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

https://ko.wikipedia.org/wiki/%EC%9D%B8%ED%84%B0%EB%9F%BD%ED%8A%B8_%ED%95%B8%EB%93%A4%EB%9F%AC
https://ko.wikipedia.org/wiki/%EB%AA%85%EB%A0%B9_%EB%A0%88%EC%A7%80%EC%8A%A4%ED%84%B0

- CPU에서 프로그램을 실행하고 있을 때 입출력 하드웨어 등의 장치에 예외상황이 발생하여 처리가 필요할 경우에 CPU에게 알려 처리할 수 있도록 하는 것

- != [Polling (폴링)](https://ko.wikipedia.org/wiki/%ED%8F%B4%EB%A7%81_(%EC%BB%B4%ED%93%A8%ED%84%B0_%EA%B3%BC%ED%95%99))
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

- 인하우스 툴  
- 튜플
- 에라토스테네스의 체  
- Leading 0  
- 요세푸스 문제
- Argument <> Parameter  
- URI  
- WebRequest  
- gcc  
- 공변성과 반공변성  
- in 제네릭 한정자  
- in 매개변수 한정자  
- 커널  
- 시암의 방법  
- System.Random Unity.Random 차이
- format  
- vendor  
- 다중 사용자 시스템, 단일 사용자 시스템  
- 모뎀  
- company  
- solution  
- centor  
- suite  
- address  
- data transfer  
- 전송 매체 Transmission Medium  
- device  
- Ethernet  
- Traffic  
- Internet Communication ?  
- Cell Phone  
- OSI  
- 멀티캐스트  
- FFT 고속 푸리에 변환  
- lower_bound, upper_bound
- cin.fail  cin.eof  여러 줄 입력 끝 판단  
- scanf printf 도 malloc 을 사용한다 >> 힙 할당이 생긴다  
- C 메모리 구조  
- C for문 안에서의 변수 선언 불가능 ? Cpp 컴파일러가 읽어서 가능? 
- 메모리 누수, 댕글링 포인터  
- 이 문제를 알아서 해결해주는 것이 GC  
- 문자열 리터럴 풀 = 전역변수가 저장되는 곳  
- 문자열 > 프로그램 내에서 어디든지 사용 가능 = 전역 변수  
- 메모리 접근 > OS  
- 왜 시작 위치만 저장하느냐> 문자열 자체가 끝에 \0 을 가지고 있기 때문
- 버퍼 입력버퍼 버퍼링  
- 주사 방식  
- scanf 의 scan 주사  
- HW  
- 관리 커널  
- 조게껍데기 셀  
- 커널 셀 ㅡ 운영체제  
- 사용자 프로그램  
- 유저 입력  
- 입력 명령 해석 셀  
- 셀에서 실행  
- 셀 명령러 해석기  
- Bar Cmd Exe 확장자 차이  
- 단말기 = 터미널  
- 맨 마지막, SW에 있어서 최종 소비자  
- SOP  
- snippet  
- 서드파티  
- pretty much (of)  
- 너무 이른 최적화  
- 전처리기 지시어  
- Reference Counting  
- STL Vector vs Array  
- 순람표 룩업 테이블  
- C# default  
- Unity curve.Evaluate(  
- 로렘 입숨(lorem ipsum;  
- 머신 사이클  
- 바인딩 타임  
- 미나렛  
- “Unfortunately this was not humanly possible”
- music plays
- “Until”
- 아킬레스 거북이  
- 사실관계적시  
- b2b  
- 엠비? 엠바고  
- 백일하  
- 화투 배경에 메이드
- 엘리베이터 문을 열었는데 엘리베이터가 나온다
- 날씨도장
- 땅버섯
- 검은 합창단  
- 흰색 빨간색, 신 붉은 창  
- 우두머리 머리 하얀 손 마름  
- 아이 머리 하얀 손  
- 신 HW 우두머리 SW  
- 샤프트 각도
- 가시 선인장  
- 초야
- 파타모르가나  
- 태양 기둥  
- 고전  
- / 프리랜서의 핵심은 자유인데 오히려 반대  
- 자유는 무한 책임, 무한 책임은 불안, 불안은 필요 이상의 자기 통제  
- 그럼에도 불구하고, 완벽한 외적 자유를 가지고 산다는 느낌 자체가 좋다  
- 학창 시절에 선생님 수업 무시하고 내 방식대로 공부하는 느낌과 비슷하다.  
- / 불안이든 외로움이든 자기 통제의 강박이든 일정 수준을 넘으면 스트레스가 되고  
- 스트레스는 '반드시' 신체 건강에 영향을 준다고 생각  
- 길게 보시고 롱런하시길 바라렉요. 다른 말로 건강 챙기면서 하시라는 말이에요  
- / 뽀모도로 기법  
- aa ASCII ART
- 공감주의  
- / 코드가 더러워도 좋으니 일단 완성을 해라,  
- 코드 퀄리티는 완성보다 우선시되면 안된다  
- / 개발 실력을 생각하면 자괴감만 들게 되어있다  
- 생각해야할 것은 내 개발 실력이 아니라 해결해야한ㄴ 문제  
- 문제 해결책에 집중할 때 비로서 엉뚱한 우울감에 빠지지 않은  
- / 공부는 정통으로  
- 하지만 구현은 꼭 정통일 필요는 없음  
- / 부전나비  
- / 동물이나 사람의 행동을 생물학적-진화론적으로 분석해보는 습관이 있다. 물론 그런 분야에 관해 전문적인 지식을 가지고 있거나, 제대로 공부해본 것은 아니지만, 나름의 논리대로 상식선에서 분석해보는 것이다. 예를 들어, 우리는 왜 어두운 곳을 두려워 할까? 우리는 왜 높은 곳을 두려워 할까? 같은 질문을 나름대로 분석해보자면 다음과 같다. 지금처럼 밤만 되면 환하게 세상을 비추는 가로등이나 언제 어디서든 빛을 낼 수 있는 손전등은 저 먼 옛날에는 존재하지 않았고, 때문에 어두운 밤이나, 깊은 동굴은 야생 동물에게 공격당할 위험성이 있었을 것이다. 때문에 어두움을 두려워하지 않은 인류는 살아남기 힘들었고, 반대로 어두움을 두려워한 인류는 상대적으로 살아남을 가능성이 높았다. 높은 곳을 두려워하는 이유도 앞의 이유와 비슷하다. 이런 식으로 내가 가지고 있는 상식 선에서 동물이나 사람의 행동, 본능을 분석하는 것이다. 하지만 어릴 때부터 풀리지 않는 의문이 하나 있다. 과연 사랑이란 무엇일까? 이 질문은 도저히 내 상식 선에서 대답할 수 없었다. 일반적으로, 사랑하게 되는 주된 이유는 외모다. 그런데 외모가 생존에게 주는 이점이 있다고 볼 수 있을까? -> 사회적 동물
- i love egg
- 비바리움  
걍 땅 캐는거?
뒷산에서 보석캐기?
디펜스랑 방치랑 합치면..?
님블궤스트?
소울나이트
피하기?
지하철
팬텀오브스칼렛?
어떻게 4.8점대지
광부 돌ㄹ캐고 광물로 장비만들어서 싸우는?
광부는 방치 장비는 뭔가
광부 모험가 마녀?
탱 딜 힐
마녀 포션이랑 연구
모험가 그냥 방치느낌?
잡템 찾아오는
광부 모험가 장비 ?
대장장이?
브라우저 확장으로
이모티콘 점수
++ ++ a O
a ++ ++ X
오른쪽에서 왼쪽으로 실행되기 대문에
무튼 연산자 만들 때 그래서 위쪽은 되게, 아래쪽은 안되게 만들어야함
이걸 간단히 구현하게 해주는 방법이 있음
-
객체& operator++() 에서 &을 붙여주는 이유
예를 들어 Temp a = v1 + v2 를 봤을 때
v1 + v1 의 결과값은 임시 객체임, v1이나 v2의 실체 객체가 아니라는 것
이를 바탕으로 ++ ++ a 를 보면
객체를 반환값으로 보내면
a = a + 1 에서 a(왼쪽) 를 반환하지 않고 a + 1(오른쪽) 의 임시 객체를 보내버림
그래서 자기 자신을 반환하기 위해 레퍼런스를 보냄
화산회
번개회
뢰
꽃 메이드 메카닉
망상키우기
알바뛰는 마왕님
거꾸로 된 파테마
썸머우저ㅡ
유루캠
낮잠 공주
파프리카
https://youtube.com/shorts/WzK97Y1aJ_w?feature=share
- 맥거핀

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
- despite
- imprecisions  
- RTFM  
- get rid 제거하다  
- violation 위반  
- predicate  
- approach 학문이나 연구 등에서, 대상에 접근하는 일  
- wears out 닳다
- last indefinitely 무기한 지속
- troubleShooting 문제해결
- straightforward 똑바로  
- indicate 나타내다 =? 지시자  
- superfluous 불필요한  
- biography  
- determine  
- toc  
- narrow  
- reasonable  
- arbitary  
- subsequence  
- adjacent  
- nive  
- intuitive  
- calibration  
- agile  
- parse  
- sudo  
- assuming  

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

### 🎲 C# [접근 한정자/Access Modifier](https://learn.microsoft.com/ko-kr/dotnet/csharp/language-reference/keywords/access-modifiers)  

---

public  
protected  
private  
internal : 동일한 어셈블리 내에서만 접근 가능  

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

### 🎲 var let const  

---

JavaScript에 대하여,  

| var | 중복 선언 가능 | |  
| let | 중복 선언 불가능 | 값 변경 가능 |  
| const | 중복 선언 불가능 | 값 변경 불가능 |  

중복 선언이 가능하다는 var의 특징 때문에, let이 나온 이후로는 변수 선언 시 let과 const를 주로 사용  
호이스팅, 스코프 관련해서도 다른 점이 있다고는데, 패스  

- var : Variable
- let : Let
- const : Constant

### 🎲 수학 기호

---

[링크1](http://daplus.net/github-github-markdown-%ED%85%8C%EC%9D%B4%EB%B8%94%EC%97%90-%EC%B2%B4%ED%81%AC-%EB%B0%95%EC%8A%A4-%EB%98%90%EB%8A%94-%EB%88%88%EA%B8%88-%ED%91%9C%EC%8B%9C%EB%A5%BC-%EA%B7%B8%EB%A6%AC%EB%8A%94/)
[링크2](https://ko.wikipedia.org/wiki/%EC%9C%84%ED%82%A4%EB%B0%B1%EA%B3%BC:TeX_%EB%AC%B8%EB%B2%95)
[링크3](https://namu.wiki/w/%EC%88%98%ED%95%99/%EC%95%BD%EC%96%B4%20%EB%B0%8F%20%EA%B8%B0%ED%98%B8)
[링크4](https://ko.wikipedia.org/wiki/%EB%85%BC%EB%A6%AC_%EA%B8%B0%ED%98%B8)
[링크5](https://zetawiki.com/wiki/%EC%9E%90%EC%97%B0%EC%88%98%EC%A7%91%ED%95%A9,_%EC%A0%95%EC%88%98%EC%A7%91%ED%95%A9,_%EC%9C%A0%EB%A6%AC%EC%88%98%EC%A7%91%ED%95%A9,_%EC%8B%A4%EC%88%98%EC%A7%91%ED%95%A9,_%EB%B3%B5%EC%86%8C%EC%88%98%EC%A7%91%ED%95%A9)

### 🎲 VRChat World에서 VideoPlayer로 데이터 불러오기

---

[링크1](https://feralresearch.org/lab/api-calls-from-inside-vrc/)
[링크2](https://ask.vrchat.com/t/http-requests/1803)
[링크3](https://github.com/Roliga/udon-video-decoder)
[링크4](https://gitlab.com/anfaux/pixel-proxy/-/blob/main/server-node/modules/encode.js)
[링크5](https://vrchat.com/home/launch?worldId=wrld_7508e408-ba6a-4478-b772-6af430c89286&instanceId=51500~private(usr_74fd4823-008f-4434-969c-c892e7c143e2)~region(eu)~nonce(031b2879-124f-4943-b075-2700f61ee200))

### 🎲 무지성 복사  

---

[VA-11 HALL-A](http://waifubartending.com/)

[블로그](http://wookje.dance/)
[블로그](https://shoark7.github.io/)

[셀레스트의 보이지 않는 구현](https://gall.dcinside.com/mgallery/board/view/?id=celeste&no=1177)  
[리스크 오브 레인 2 - 소환 루프](https://riskofrain2.fandom.com/wiki/Directors#Spawn_loop)  
[Github Remote Disconnected](https://github.com/desktop/desktop/issues/14936)  
[특정 구역에서의 랜덤 스폰 알고리즘](https://gall.dcinside.com/mgallery/board/view/?id=game_dev&no=89582&exception_mode=recommend&page=1)    
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
[유니티 Vector3는 스택에 생성된다, 값 형식이다, Struct](https://3dmpengines.tistory.com/1566)  
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
[Pope Kim - 전처리기](https://blogofth-lee.tistory.com/281)  
[Pope Kim - 문자열 해쉬](https://blog.popekim.com/ko/2012/01/11/compile-time-hash-string-generation.html)  
[C# Foreach](https://m.cafe.naver.com/ca-fe/web/cafes/26377973/articles/122961)  
[C# vs CPP](https://moguwai.tistory.com/entry/C%EA%B3%BC-C%EC%9D%98-%EB%AC%B8%EB%B2%95%EC%A0%81%EC%9D%B8-%EC%B0%A8%EC%9D%B4%EC%A0%90)  
[위키독스 - 온라인 책 공유 플랫폼](https://wikidocs.net/)  
[OpenGraph](https://blog.ab180.co/posts/open-graph-as-a-website-preview)  
[URI-URL](https://velog.io/@jch9537/URI-URL)  
[마인크래프트 지형 생성 알고리즘](https://blog.naver.com/kids1412/222686829072)  
[코딩 테스트 및 알고리즘 문제해결 공부 방법](https://www.slideshare.net/SuhyunPark23/kucc-2022-4)  
[[C++] 코딩테스트를 위한 C++ 기본](https://suyeoniii.tistory.com/13)  
[코딩 테스트 입문 (with C++)](https://gamedevlog.tistory.com/6?category=892157)  
[알고리즘 공부 방법/순서](https://baactree.tistory.com/14)  
[[알고리즘] 아호 코라식(Aho-Corasick) 알고리즘](https://pangtrue.tistory.com/305)  
[[알고리즘] KMP(Knuth-Morris-Pratt) 알고리즘](https://pangtrue.tistory.com/303?category=724827)  
[[자료구조] Trie(트라이)](https://pangtrue.tistory.com/331?category=724827)  
[동적 계획법](https://namu.wiki/w/%EB%8F%99%EC%A0%81%20%EA%B3%84%ED%9A%8D%EB%B2%95)  
[메모이제이션](https://namu.wiki/w/%EB%A9%94%EB%AA%A8%EC%9D%B4%EC%A0%9C%EC%9D%B4%EC%85%98)  
[DP의 기본에 대해서...](https://stonejjun.tistory.com/23)  
[변수명 짓기](https://www.curioustore.com/#!/)  
[C++ 익명함수 사용법](https://progl.tistory.com/5)  
[함수호출규약](https://blog.kimtae.xyz/7)  
[vscode (visual studio code) tab to space 또는 space to tab 변환](https://moaimoai.tistory.com/311)  
[C#을 다루는 기술](https://thebook.io/080201/)  
[C# - int []와 object []의 차이로 이해하는 제네릭의 필요성](https://www.sysnet.pe.kr/2/0/11805?pageno=0)  
[프로그래밍/C Sharp[C#] 비트연산 처리 모음](https://jeong-f.tistory.com/96)  
[[C#]List 속성별로 정렬](https://developer-talk.tistory.com/220)  
[Convertio](https://convertio.co/kr/)  
[게임제작에 사용되는 영어단어](https://m.blog.naver.com/PostView.nhn?blogId=nicecapj&logNo=130062005836&proxyReferer=https:%2F%2Fwww.google.com%2F)  
[c# parse convert 차이](https://2-nan.tistory.com/43)  
[[C#] Process 클래스 사용 예제](https://kimkitty.net/archives/1638)  
[Run git commands from a C# function](https://stackoverflow.com/questions/26167387/run-git-commands-from-a-c-sharp-function)  
[Unity Tricks — How to hide a UI object that is behind a transparent UI?](https://medium.com/@cuilongchang/unity-tricks-how-to-hide-a-ui-object-behind-a-transparent-ui-2700c12372c1)  
[던그리드 0](https://gall.dcinside.com/mgallery/board/view/?id=game_dev&no=11872&list_num=30&search_pos=-15520&s_type=search_subject_memo&s_keyword=%EB%8D%98%EA%B7%B8%EB%A6%AC%EB%93%9C&page=2)  
[던그리드 1](https://gall.dcinside.com/mgallery/board/view/?id=game_dev&no=12015&list_num=30&search_pos=-15520&s_type=search_subject_memo&s_keyword=%EB%8D%98%EA%B7%B8%EB%A6%AC%EB%93%9C&page=2)  
[던그리드 2](https://gall.dcinside.com/mgallery/board/view/?id=game_dev&no=13690&list_num=30&search_pos=-15520&s_type=search_subject_memo&s_keyword=%EB%8D%98%EA%B7%B8%EB%A6%AC%EB%93%9C&page=2)  
[던그리드 3](https://gall.dcinside.com/mgallery/board/view/?id=game_dev&no=14783)  
[던그리드 4](https://gall.dcinside.com/mgallery/board/view/?id=game_dev&no=13710&list_num=30&search_pos=-15520&s_type=search_subject_memo&s_keyword=%EB%8D%98%EA%B7%B8%EB%A6%AC%EB%93%9C&page=2)  
[던그리드 5](https://gall.dcinside.com/mgallery/board/view/?id=game_dev&no=12155&list_num=30&search_pos=-15520&s_type=search_subject_memo&s_keyword=%EB%8D%98%EA%B7%B8%EB%A6%AC%EB%93%9C&page=2)  
[넥슨 커리어](https://career.nexon.com/common/main)  
[UNITY에서 코딩 시 VISUAL STUDIO 툴 최적화를 위한 팁](  https://unity.com/kr/how-to/tips-optimize-your-visual-studio-tools-when-coding-unity)  
[HITS](https://hits.seeyoufarm.com/)  
[메이플 마켓 원리](https://www.inven.co.kr/board/maple/2299/6421191)  
[C# OCR](https://m.blog.naver.com/PostView.naver?isHttpsRedirect=true&blogId=rhukjin&logNo=222052759608)  
[패킷](https://enlqn1010.tistory.com/9)  
[메이플 패치파일](https://www.inven.co.kr/board/maple/2304/9801)  
[C# Linq Take, Skip](https://afsdzvcx123.tistory.com/entry/C-%EB%AC%B8%EB%B2%95-C-Linq-Take-Skip-%EC%9D%B4%EC%9A%A9%ED%95%98%EC%97%AC-%ED%95%84%EC%9A%94%ED%95%9C-%EA%B5%AC%EC%97%AD-%EC%9E%98%EB%9D%BC%EB%82%B4%EA%B8%B0)  
[Coding 시 변수 선언 위치는 어떻게 잡아주고 계시나요?](http://1st.gamecodi.com/board/zboard.php?id=GAMECODI_Talkdev&no=1461)  
[정적 멤버 직접 사용 (클래스명 생략)](https://www.csharpstudy.com/CS6/CSharp-using-static-member.aspx)  
[Change line renderer alpha unity](https://stackoverflow.com/questions/63178546/change-line-renderer-alpha-unity)  
[게임잡](https://www.gamejob.co.kr/Recruit/joblist?menucode=duty&duty=1)  
[유니티 최적화](https://helenstudy.tistory.com/51)  
[20200219[C#] GetType메서드와 typeof연산자](https://funfunhanblog.tistory.com/313)  
[우왁굳 트위치 이모티콘](https://twitchemotes.com/channels/49045679)  
[포켓몬스터 블랙/화이트 BGM 레파토리](https://m.blog.naver.com/PostView.naver?isHttpsRedirect=true&blogId=riomedevon&logNo=110106228406)  
[포켓몬스터 블랙/화이트 빌리지 브리지](https://pokemon.fandom.com/ko/wiki/%EB%B9%8C%EB%A6%AC%EC%A7%80_%EB%B8%8C%EB%A6%AC%EC%A7%80)  
[포켓몬스터 블랙/화이트 빌리지 브리지](https://namu.wiki/w/%EB%B9%8C%EB%A6%AC%EC%A7%80%EB%B8%8C%EB%A6%AC%EC%A7%80)  
[OPTIMIZATION TIPS FOR UNITY UI](https://unity.com/how-to/unity-ui-optimization-tips)  
[Coroutine과 Time.timeScale 관계](https://m.blog.naver.com/PostView.naver?isHttpsRedirect=true&blogId=dus531400&logNo=140209199573)  
[당신이 보는 게임 화면은 진짜가 아니다.](https://gall.dcinside.com/mgallery/board/view/?id=aoegame&no=16490887)  
[엔터더건전 3D 트윗](https://twitter.com/DodgeRollGames/status/593625936131653632)  
[2D도트게임의 비밀](https://www.dogdrip.net/195354145)  
[Conway's Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life)  
[메이플스토리 블로그](https://blog.maplestory.nexon.com/)  
[jekyll Liquid](https://fuzzysound.github.io/jekyll-liquid)  
[The Unity Shaders Bible](https://learn.jettelly.com/unity-shader-bible/#buy-now)  
[JekyllRB Doc](https://jekyllrb.com/docs/front-matter/)  
[Jekyll 좌측 네비바 카테고리 만들기](https://ansohxxn.github.io/blog/category/)  
[Bensound](https://www.bensound.com/royalty-free-music/track/memories)  
[Kitbash3D](https://kitbash3d.com/)  
[Mixamo](https://www.mixamo.com/#/)  
[Pixabay](https://pixabay.com/)  
[3DWareHouse](https://3dwarehouse.sketchup.com/)  
[Waifu2x](http://waifu2x.udp.jp/index.ko.html)  
[Easings - 커브](https://easings.net/)  
[Dimensions - 휴먼덴시티](https://www.dimensions.com/)  
[Hashcode](https://hashcode.co.kr/code_runners)  
[ColorBlind ColorFilter](https://www.toptal.com/designers/colorfilter)  
[GitIgnore](https://www.toptal.com/developers/gitignore)  
[Adobe Color](https://color.adobe.com/ko/create/color-wheel)  
[123APPS](https://123apps.com/ko/)  
[텀블벅](https://tumblbug.com/)  
[특수문자 모음](https://johngrib.github.io/wiki/special-chars/?utm_campaign=asb&utm_medium=blog&utm_source=awesome-blogs.petabytes.org)  
[Discohook](https://discohook.org/)  
[컬러 팔레뜨](https://lospec.com/palette-list)  
[Zapsplat](https://www.zapsplat.com/)  
[Desmos](https://www.desmos.com/calculator?lang=ko)  
[3DAPI](http://3dapi.com/)  
[PolyHaven](https://polyhaven.com/)  
[그래픽 블로그](https://rusalgames.tistory.com/)  
[AmbientCG](https://ambientcg.com/)  
[NormalMap Online](https://cpetry.github.io/NormalMap-Online/)  
[Textures](https://www.textures.com/)  
[Sketchfab](https://sketchfab.com/feed)  
[3DSky](https://3dsky.org/)  
[CGTrader](https://www.cgtrader.com/)  
[Kenney](https://kenney.nl/)  
[SoundImage](https://soundimage.org/)  
[OpenGameArt](https://opengameart.org/)  
[RealFaviconGenerator](https://realfavicongenerator.net/)  
[CSSGradient](https://cssgradient.io/)  
[Dova-s](https://dova-s.jp/)  
[SoundEffect-Lab](https://soundeffect-lab.info/)  
[99Sounds](https://99sounds.org/)  
[SoundBible](https://soundbible.com/)  
[FreeSound](https://freesound.org/)  
[FreeSFX](https://www.freesfx.co.uk/)  
[SoundJay](https://www.soundjay.com/)  
[사운드 리소스 모음](https://docs.google.com/spreadsheets/d/1GtehmgtnAX2dt5xM8Qv4Kj8-eZtGA5sRuCjw40oLI3o/edit#gid=0)  
[Soniss](https://sonniss.com/)  
[Sonniss](http://sonniss.com/gameaudiogdc#1605031061361-34588c70-73f2)  
[PlayOnLoop](https://www.playonloop.com/)  
[SimpleIcons](https://simpleicons.org/)  
[IcoonMono - 아이콘](https://icooon-mono.com/)  
[자극에 무뎌지는 감각](https://blog.naver.com/shalacho/222114284512)  
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

### 🎲 데이터베이스 관리시스템(DBMS : Data Base Management System)  

---

MySQL 핵심개발자들이 MySQL에 대한 오라클의 라이센스 정책이 자신들과 맞지 않는다
는 이유로 오라클사를 탈퇴해서 만든것이 MariaDB  
MariaDB는 MySQL의 소스코드를 그대로 사용하여 개발했기 때문에 모든 기능이 동일  
차이점은 라이센스 정책인데 MySQL은 소유권이 오라클에 있어서 기업에서 상업적으로 사용하는데 비용이 발생,  MariaDB는 오라클사와 무관하기 때문에 무료 사용이 가능합니다.(엔터프라이즈 버전은 유료지만 무료의 범위가 넓음)

### 🎲  

---

httpd의 d : daemon :  
악령 또는 그리스 신화에서 초자연적인 존재 :  
User가 직접 제어하지 않고, 백그라운드에서 돌며 작업을 하는 프로그램 = 상주 프로그램 (resident program)

### 🎲 Inspiration

---

요정의 링 : 버섯이 고리 모양으로 자람, 서양에서는 요정들이 둥글게 모여 춤을 추면 그 자리에 버섯이 자란다는 전설, 버섯 같은 진균류의 특싱, 진균류는 곰팡이처럼 포자를 자기 주위로 퍼트리며 번식하는데, 처음에는 동글게 퍼져나가다가 가운데 부분에 영양분을 다 흡수하면 더 이상 자라지 못하고 허물어지기 때문에 고리 모양만 남게 되는 것  

흰수염고래는 세상에서 가장 큰 동물인데, 그것과 마찬가지로 흰수염 에드워드는 누구보다 마음이 넓다.  

사랑했던 사람을 닮은 사람을 보면 그 사람을 사랑한다기보단 사랑햇던 사람이 더 그리워지는 그런 기분.  

이 사람이 위로가 필요한 순간을 보았지만, 자신은 절대 그 위로를 해줄 수 없음을 알았을 때의 머뭇거림.  

시그너스 전당 - Fallen Kingdom 같은, 과거의 영광?  

Somewhere over the rainbow - 20 days after this song, World War 2 started.  

모험 - 시한부로 뒤지기 전에 돈 다 털어서 가족들이랑 세계여행하다가 마지막날에 모닥불 앞에 앉아서 한풀이 하면서 현실에는 없는 애인이랑 손잡고 밤하늘 바라보는 느낌임  

왕좌의 게임 - 웨스테로스를 기준으로 볼 때 지명이나 이름들 대부분이 상당히 토속적이다. 한국어로 번역하면서 음역해놓은 것만 보면 멋있게 느껴질 수 있겠지만, 원래 의미를 살리게 되면 아주 직설적이고 고풍스러운 지명이 된다. 대륙의 이름인 웨스테로스부터 '서쪽대륙' 정도의 의미이고, 수도인 킹스 랜딩은 '왕이 상륙한 땅', 주요 가문의 거성들 또한 '겨울언덕', '흐르는 강', '캐스터의 바위', '둥우리', '높새정원', '폭풍의 끝', '태양창'이 된다. 다만 이건 얼불노만이 그렇다고 볼 수 없다. - 사실 모든 지명, 이름 등은 원래 어원 자체가 이렇다. 하지만 다른 언어에서 유래한 것들(미국은 아메리카 원주민, 영국은 켈트족 등)도 많고, 고어로 이루어진 경우가 많다보니 현대인이 느끼기에는 어원을 깨닫지 못하고 그냥 지명으로만 인식되는 것이다. 특히 한국은 한자의 영향으로 원래의 우리말 지명이 거의 사라지고 한자식 지명만 남아서 얼음과 불의 노래 같은 고풍스러운 지명이 잘 인식되지 않는 것이다. 광주(光州)를 빛고을, 대전(大田)을 한밭이라 부르는 것을 생각해보면 깨달을 수 있을 것이다.  |  현실 세계와 유전 형질이 다르게 발현되는 듯 하다. 예를 들자면 수백, 수천년 동안 같은 은발자안, 흑발벽안, 금발녹안 등등의 형질을 유지하는 대가문들이라던가... 형질을 유지하는 덕분(?)에 대가문의 사생아 확인이나 부인의 불륜 의혹을 쉽게 알아 낼 수 있는 듯 하다. - 존 아린과 에다드 스타크는 흑발이 우성인 바라테온 가문 사람임에도 어머니를 닯은 금발의 세 남매를 보고 세르세이가 불륜을 저질렀다는 걸 쉽게 알아냈다.  

16살때가 아침에 울면서 일어난적이 있는데 분명 일어난 직후엔 꿈 내용 기억했는데 몇 분 정도 흐르니깐 암것도 기억안남 ㅋㅋㅋㅋ 부모님이 와서 왜우냐고 하니까 몰라 그냥 우는 중이야 라고 말했던 기억이 ㅋㅋㅋㅋ  

인적마저 끊긴 마을에 언젠가 사람들이 돌아올 것이라고 기다리며 노래 만들고 있는 해골 - 진짜 브룩이네 !  

You know you're dead when the crowd is singing the other team's theme.  

뭔가 저승사자가 생전 붉은 실로 이어져있던 연인을 그리며 부르는 노래같음 ㅇㅇ.  

멜랑꼴리  

One Piece | All Eyecatchers  

난 늘 원피스 볼때 노력하고 누군가를 존경하는 애들이 좋더라~  

일반인에게 집을 그려보라라고 한다면, 지붕을 그린 뒤 기둥을 그리고 문을 그려넣지만,  
전문 기획자, 혹은 설계실무자에게 '집을 그려보자' 라고 한다면 토대를 만들고 기둥을 세운 뒤 지붕을 올린다고 하지요 ㅎㅎ  

1 개인적으로 주술같은 것을 쓰는가 아닌가 차이같더라고요. 오히려 저는 주술사와 샤먼과 마녀의 차이가 뭔지 고민하는데 뚜렷한 답은 안나오고요.  
2 일단 각자가 가진 이미지가 뚜렷하다고 생각되네요. 마녀의 경우는 빗자루, 가마솥, 물약 등의 연상이 자연스레 되고, 샤먼은 토템같은 매개체를 갖고 있으니까요.  
1 이미지를 생각못하고 능력만 생각했었네요.  

오파츠 OOPARTS Out-Of-Place ARTifactS 시대를 벗어난 유물  

개에게 물린 상처는 개를 죽인다고 아물지 않는다  

박테리아들은 우리 몸의 면역체계를 뚫기 위해 진화해 왔어. 그렇기 대문에 네가 만약 미래로 시간여행을 한다면 넌 죽을거야. 반대로 네가 과거로 시간여행을 한다면, 과거 사람들이 다 죽겠지. - 혹사병이나 스페인 독감이 어떤 XX 같은 시간여행자 때문이였던거 아냐?  

관찰자 없는 우주의 의미, 존재 하는가?  

노래가 울려퍼지는 이 순간만큼은 몽환의 세계에 있는 것 같아서 좋다  

플라톤의 사원소설에 의하면 정십이면체는 우주에 해당하는데 시그마는 두 개의 정십이면체 초구체를 들고 있네요.  

알 - <https://terms.naver.com/entry.naver?docId=630308&cid=50766&categoryId=50794>  

마법소녀가 누구나 구해야하는건 아니죠  

마법소녀, 히어로들이 사람들을 구하기 위해 있는 존재? 지구를 지키는 이유는 본인의 평범한 일상을 유지하고 살아가기 위해서이다. 본인이 평범한 일상을 사는데에 방해되는 존재를 굳이 도와주어야할 이유가 있는지?  

무지하고 무식하기 짝이없는 무지막지한 세상에 홀로 떨어진, 단 한 명의 지식인 마냥 고통스러워보인다.  

배고픈 자는 수저가 없어도 밥을 먹는다  

지금 편한 이유는 내리막길을 걷고있기 때문이다  

맑은 날이 계속되면 가뭄이 온다  

캐릭터를 성장시키는 것이 아니라 플레이어가 성장하는 게임  

미쿠미쿠 - <https://www.inven.co.kr/webzine/news/?news=110890>  

라이트 모티브 - 극에서 어떤 인물이나 감정 등 특정 주제에 대해 전용 테마곡을 만들고 극의 흐름에 따라 바리에이션을 시키는 것  

제노사이드 - 인종, 이념 등의 대립을 이유로 특정집단의 구성원을 대량 학살하여 절멸시키려는 행위  

우리나라 신석기 시대 고래 사냥?  

마라분타 - 군대개미 <https://youtu.be/ulhbLCJ-UOA>  

판도 Pando 라는 군락, 뿌리가 하나로 연결되어 있는 모든 줄기들이 하나의 개체, DNA 상 전부 하나의 나무  

Elysia chlorotica - 푸른 민달팽이  
흔한 나뭇잎 의태족, 초록색을 내기 위해서 먹이를 먹을 때 전부 소화시키는게 아니라 엽록체를 산채로 장에 보관, 처음에는 엽록체를 유지하기 위해 계속 해조류를 먹어야 함, 나중가면 내장세포와 엽록체가 합체되어 더 먹지않아도 됨, 광합성으로 빛에서 에너지도 얻을 수 있게 됨.  

물 속에서 터진 탄환은 꽃과도 같아서 인어는 그것이 무엇에 스인 줄도 모르고 마냥 예뻐하며 인간세계를 동경할 것 같다는 이야기가 있죠  
ㄴ 미확인  

초록색 렌즈, 눈을 뚫어지게 보시다, 학생 눈에도 여름이 왔네요 싱그럽고 예뻐요  

'한'  

비익조 - 한 마리의 새가 날개가 하나 뿐이어서 한 쌍이 붙어야만 비로소 날 수 있다.  
연리지 - 뿌리가 다른 두 나무가 자라 올라가면 가지가 붙어 하나의 나무가 되는 신비로운 자연 형상  
이의 합성어인 비익연리는 일생을 함께할 짝으로 영원한 사랑을 뜻한다  

뒷집 도령이 앞집 낭자보고 가슴뛰는 소리야  

포기하고 싶을 때 니가 왜 시작했는지 기억하라  

남이 하는 일들이 쉬워 보인다면 그 사람이 잘하고 있기 때문이다  

당신이 만나는 모든 사람들은 당신이 전혀 모르는 전투에서 각자 싸우고 있습니다. 언제나 모두에게 친절하게 대하세요  

Three stages of life : 1. Birth, 2. What the fuck is this, 3. Death  

법사는 체력이 낮고 강한 공격을 쓰고  
전사는 체력이 좋고 근거리공격을 쓰고  
궁수는 멀리서 화살을 쏘며 공격을 해주고  

이무기 - <https://folkency.nfm.go.kr/topic/detail/5602?pageType=search&keyword=%EC%9D%B4%EB%AC%B4%EA%B8%B0>  

take five - 2017  

운도 - 구름과 파도를 아울러 이르는 말, 물결치듯이 사납게 일어나는 구름, 멀리 수평선에 보이는 파도.  

이랑 - 갈아 놓은 밭의 한 두둑과 한 고랑을 아울러 이르는 말  

두둑 - 논이나 밭 가장자리에 경계를 이룰 수 있도록 두두툭하게 만든 것 [비슷한 말 두렁].  

푸르다 유의어 - 청청, 싱싱, 쾌청, 푸르뎅뎅, 창창, 푸르스름, 푸르죽죽하다  

언덕  

섞이지 않는 바다 - 다른 염분 농도때문에 만나도 섞이지 않는 발트해와 북극해의 자연현상  

검은 장미 - 터키의 할페티라는 곳에서만 자연적으로 존대한다  

과일 샐러드 나무는 실제로 존재한다 - 그 나무들에서는 7개짜기의 다른 종류의 과일들이 동시에 열린다  

고양이는 상대방이 자신의 소유임을 알리기 위해 상대방의 얼굴에 문지른다. 고양이가 당신의 얼굴을 문지른다면, 당신이 가족으로서 인정 받았다는 말이다.  

바오밥 나무는 천 년이 지나면 자연적으로 속이 텅 비게 된다.  

Mortgage - 담보는 "죽음의 계약"을 의미하는 프랑스 단어에서 유래되었다  

아구는 짝짓기를 할 때, 몸을 녹여 서로 융합시켜 영원히 몸을 공유한다. 만약 수컷이 암컷을 찾으면, 수컷은 암컷에게 들러붙어 서로 합체한다. 이 과정에서 수컷은 둘이 혈관을 공유할때까지 장기 일부를 잃게 된다.  

스켈레톤 프라워는 섬세한 꽃잎들을 가지고 있는데, 이들은 비가 내리면 투명화된다.  

캐나다에는 점박이 모양의 호수들이 있는데, 대부분의 물이 열에 증발하고 물웅덩이에 화려한 광석 퇴적물들이 남는다.  

반딧불이들은 현대의 전등보다도 더 효율적인 빛 생산을 한다.  

대부분의 거미들은 거미줄에 쓰이는 실크 단백질을 재활용하기 위해 자신의 거미줄을 섭취한다.  

촛불은 타면서 수백만개의 작은 다이아몬드를 소모하는데, 이는 그들이 탄소 4개의 형태 (다이아몬드의 화학적 구조)를 포함하고 있기 때문이다.  

국가 아랍 에미리트는 기후를 바꾸기 위해 산을 건설할 생각을 심각하게 고민중이다.  

매우 독성이 강한 나무가 있는데, 비에 흠뻑 젖은 이 나무의 잎사귀는 당신의 피부를 태워버릴 것이다. 이 나무는 Manchineel 대극과 나무라고 불린다.  

다윗의 별, 렘판의 별, 이스라엘 국기  

사대문은 서울 성의 사방문과 가운데 보신각을 의미  
북 검정 현무 오상:지 지식 송지문  
동 파랑 청룡 인 어질 홍민문  
서 하양 백호 의 뜻 돈의문  
남 빨강 주작 예 예도 숭례문  
중 노랑 황룡 신 믿을 보신각  

무언가를 찾아나서는 도전은 언제나 '초심자의 행운' 으로 시작된다. 그리고 반드시 가혹한 시험으로 끝을 맺는다  
파울로 코멜료 - 연금술사  

메타픽션  

사람들은 아무도 없고 오직 몬스터와 나 밖에 없다  

4대 문명 - 문자를 기록하고 사용하는 데에 보편화된 사회  
문명의 시작을 알리는 '문자'가 사요된 점에서 반영한 것이다.  
문명은 한자 그 자체의 뜻으로서도 글자 문, 밝을 명, 문자를 밝힌다 (개척한다) 이다  

베르세르크  

카르다쇼프 척도  

베네수엘라 엔젤 폭포  

크레타섬의 3000년 된 올리브 나무  

Nazars  

호랑이는 순우리말로 칡범 혹은 갈범이라고 했는데 저 떡 뺏어먹는 호랑이는 영조시절 오일장을 위해 미시령을 넘나들던 상인들에게 빈번하게 떡을 뺏어먹는다는 사실이 조선와조실록에 기록되어 있습니다. 마을 뿐 아니라 조정에도 그 소문이 파다하게 퍼졌고, 후에 저 호랑이는 수시로 저런 짓을 벌인다 하여 상습범이라 불리게 되었다는 기록도 있네요.  

발광하는 식물성 플랑크톤  

신은 모든 곳에 있을 수 없기에 어머니를 만들었다  

회드, 켈트 신화, 참나무를 아는자 혹은 숲을 나는자, 자연 숭배를 기본으로 하는 사제나 지식인  

번개, 신경계 손상을 비롯해 피부 흉터인 '리히텐베르크 무늬'  

성당 가고일이 지키는  

가장 진한 어둠은 가장 흐린 빛에도 사라진다  

초능력자, 총잡이, 성기사, 야만용사, 연금술사, 마법사, 아마조네스, 비재능자  

하이퍼 라이트 드리프터 - 갑자기 나타난 정체불명의 검은 존재에 의해 파괴된 세상에서 검은 존재에게 맞서다가 생긴 치명적인 병을 치료하기 위해 고군분투하는 한 방랑자  

the-right-writing

1. 캐릭터가 늙어죽게 하지 말아라.
(물론 다른 요소들이 충분히 있다면 상관없을 수도 있다.)

2. 캐릭터가 추구하던 중요한 목표를 이루지 못했을 때 죽여라.
해당 목표를 더 열정적으로 이루려고 노력했을수록 죽음은 더 슬퍼진다. 

3. 다른 캐릭터와 굳건한 관계를 이루게 한 뒤 죽여라.

4. 죽음의 원인에 맞서 싸우게 한 뒤 죽여라.
발버둥 치다 결국 실패한 뒤 상실을 맞게 하라.

5. 캐릭터의 발달이 한창 이루어지던 도중 죽여라.

6. 캐릭터의 장례식에 대한 묘사는 너무 세세히 묘사하지 말아라.

MarshyMellow

7. 목숨을 하찮게 보이게 만드는 죽음 방식을 선택하라.
만일 캐릭터가 제국을 구한 전사였다면, 딸의 간식을 사러 나갔다가 골목에서 강도에게 죽게 하라.

8. 캐릭터의 죽음보다는 죽음 이후 주변 인물의 붕괴에 더 주목 하라.

socialjustliceprincesses.tumblr.com

9. 캐릭터의 죽음/장례식 때 노래를 넣어라. 그 노래를 들을 때마다 팬들이 슬퍼하도록.

asbehsam.tumblr.com

10. 캐릭터가 농담을 하거나, 미소 짓거나, 즐거움/행복을 보이고 있는 도중 죽여라.

11. 느리고 고통스럽게 죽여라.

12. 직전에 해당 캐릭터의 의외의 일면을 드러낸 후 죽여라.
(항상 터프하고 용맹하던 캐릭터가 죽는 것을 진심으로 두려워한다던가,
항상 밝게 웃던 캐릭터가 죽기 전에 눈물을 흘린다던가, 혹은 그 반대)

13. 캐릭터가 뭔가 오해하도록 만든 후 죽여라.
(캐릭터가 자신이 배신당했다고 생각하거나, 사랑하던 이가 자신을 버렸다고 믿도록 하고 오해를 풀 틈을 주지 않고 죽여라.)

14. 죽음 이후 캐릭터가 모함당하도록 만들어라.
사망한 캐릭터가 오해받고, 배신자로 낙인찍히고, 미움받고, 독자들만이 진실을 알고 지켜보도록 만들어라.

15. 또 다른 사랑받는 캐릭터에 의해 살해당하도록 해라.
죽은 캐릭터를 항상 곁에서 응원하던, 팬들이 모두 좋아하던 캐릭터에 의해

reddit.com/r/FanTheories - slightlysadist

16. 캐릭터가 살 수 있었음을 보여 주어라
다른 선택을 했으면 죽지 않았을 수도 있지만 이타적 이유로 죽음을 무릅썼다던가,
그 캐릭터를 구해줄 수도 있었을 파트너가 아주 사소한 다툼 때문에, 혹은 그 캐릭터의 깜짝 생일 파티 준비 때문에 하필 그 시간 그 자리에 없게 하라.  

사라지는게 아니야 우리들만 아는 비밀로 되는거야  

그냥 모든거 다 내려놓고 하늘하늘거리게 겨울 햇살에 몸을 비쳐서 따스한 침대에 옆에 뀰껍질까놓고 그러고 2시간만 잠들다가 해질녘 즈음 일어나서 하늘로 들어가고 싶네.  

충분히 무언가를 타인에게 시킬 수 있는 위치에 서 있음에도 불구하고 시켜야 할 일 조차 시키지 못하는, 권위를 전혀 활용하지 못하는 소심한 인간상이었다. 이러한 성격이 물론 자신의 지식적인 권위를 높이는 데엔 큰 기여를 했을 것이다. 남에게 맡겨야 할 일 조차 자신의 손을 거쳐가고, 또 그렇게 자신의 손을 거쳐가면서 그 '거쳐갈 일' 과 관련된 또 다른 지식이 자신의 손에 들어왔을 테니 말이다. 하짐나 이제 더 이상 그는 그럴 필요가 없었다. 오히려 적재적소에 인원을 배치하여, 더욱 나은 연구를 이끌어내야 하는 '관리자' 라는 위치에 서 있기 때문이었다. 그런 그였으나, 여전히 그 소극적인 성격을 변화시키지 못하고 그 결과, 상급자를 하대하는 연구소의 분위기를 자아내고 말았다. 연구소의 상하 관계가 말 그대로 '엉망' 이었다. 그는 언제나 이런 자신의 성격이 싫었다. 막말로 찌질하다고 할 수 있을지도 모르겠다. 하지만 그에게 있어 이러한 소극적인 성격은 뒤틀린만한 어둠을 제공하기엔 충분하고도 남았다. 외지인에 의해 뒤틀린 이후, 그는 안경을 벗어 던지고 선글라스를 끼기 시작했고  

시리도록 눈이 부시다  
달빛에 눈이 부실리가 없다. 주로 태양빛에 눈이 부신다는 표현을 쓰지. 시리도록 눈이 부시다는 눈에 고인 또는 흐르는 눈물에 달빛이 반사되어 발짝하는 이런 느낌 있잖아요 그때 그 눈물 흘러서 차가운 밤공기에 눈 주위가 시린거고 그 반짝하는 비유가 부시다는 걸로 씁니다.  

가뭄으로 인해 드러난 저수지 아래의 400전 교회  

지구적 강함 - 단력, 잠재적 에너지, 진화, 각성  
우주적 강함 - 누가 더 높은 차원의 힘을 사용하나  

낙천적 - 세상과 인생을 즐겁고 좋은 것으로 여기는. 또는 그런 것  

무협 영화에서 어느 고수가 바위에 한자 세겨넣듯이 그런 연출을 이용한 게임은 어떨까요?  
마법천자문..?  
제스처인식은 어떨까요? 예를들어 한자의 획을 인식해 공격이나 마법등을 사용한다거나 하는거죠.  
예전에 어떤 문화책에 '문자귀술법' 이라는 기술이 있었는데, 호랑이 호 자를 쓰면 글시에서 호랑이가 튀어나와 적을 공격하는 뭐 그런...  

무기력하다 - 어떠한 일을 감당할 수 있는 기운과 힘이 없다.  

한심하다 - 정도에 너무 지나치거나 모자라서 딱하거나 기막히다, 마음이 서늘하다  

게으르다 - 행동이 느리고 움직이거나 일하기를 싫어하는 성미나 버릇이 있다.  

우울하다 - 근심스럽거나 답답하여 활기가 없다, 근심스럽거나 답답하여 활기가 없음  

근심 - 해결되지 않은 일 때문에 속을 태우거나 우울해함  

우주에서 술집을 열면? - 스페이스바  

생물발광  
슈퍼셀 - 토네이도의 원인이 되는 거대한 적란운  
화산번개 - 화산 폭발로 인한 번개  
스노우 도너츠 - 바람등에 의해 도너츠모양으로 말린 눈  
수평 무지개 - 대기 중 얼음 알갱이에 햇빛이 굴절되어 거의 수평으로 무지개가 보이는 광학 현상  
렌즈구름 - 볼록 렌즈와 같은 모양을 한 구름  
오로라 - 천체의 북극 부근에서 발견되는 대기의 발광 현상  
화재선풍 - 화재 등에 의해 발생한 화염을 동반 선풍  
Finnish Lapland - 핀란드 라플란드 지방에 눈이 쌓인 나무  
환일현상 - 대기에 더있는 미세한 얼음 결정에 태양 빛이 굴정되거나 반사되면서 프리즘처럼 보이는 현상  
스카이펀치 - 원형의 틈새가 열려있는 구름  
프로스트 플라워 - 공기 중의 수증기가 얼음이나 바위 등의 표면에 부착하여 얼어 붙어 꽆잎과 같은 형태로 성장한 것  
주상절리 - 용암이 흐르다가 바다와 만나면서 굳을 때 육각 기둥모양으로 굳어져 생긴 지형  
페니덴츠 - 해발 4000 미터가 넘는 고산에서 드물게 생성되는 몇 센티 부터 몇 미터 정도의 날카롭고 뾰족한 얼음 탑  
빛 기둥 - 일출 또는 일몰 시 태양에서 수평선에 수직 방향으로 불꽃 모양의 빛이 보이는 현상  
모닝글로리 - 호주 북부에서 잘 볼 수있는 아침을 중심으로 나타나는 거대한 롤 모양의 구름 띠  
용오름 - 토네이도가 수면에 발생한 것  
헤스달렌의 빛 - 1900년경부터 노르웨이 헤스다렌에서 목격 된 수수께끼의 빛, 플라즈마와 UFO 설도 있음  
Brinicles - 바다 속을 소용돌이하면서 급속냉각시키는 자연 현상  
지진광 - 지진 발생으로 인한 지면에서 방출되는 기체가 공기 중의 산소, 오존과 결합해 생기는 현상  
구상번개 - 뇌우가 심할 때 드물게 나타나는 공모양의 번개  

해적 첨 나왔을때 하도몰려서 NPC가 파는 템이 매진이 됐는데 어이가 없어서 쉬팔  

새로 나온 맵이라, 전직들이 찾는 곳이라 호기심에 가곤 했죠,  

메멘토모리  

나바호 인디언  
네가 세상에 태어날 때 너는 울었지만 세상을 기뻐했으니,  
네가 죽을 때 세상은 울어도 너는 기뻐할 수 있도록 그런 삶을 살아라  

아라홍련  

삼도천 - 이승에서 저싱으로 갈 때 건너게 되는 강이에요  

금사경  

성베드로는 예수님으로부터 천국의 열쇠를 받았다고 알려지고 있으면, 그 대문에 종종 천국의 수문장으로 묘사된다 그러므로 성베드로가 내 이름을 부르지 않는 다는 것은 천국에 가지 못한다는 뜻  

브로니클 Brincle  
1960 남극에서 처음 발견된 현상으로 바닷속이 어는 형상  
이것이 지나가면서 주변의 모든 생물을 얼려 죽이기 때문에 별명이 죽음의 고드름 또는 죽음의 기둥이라고 한다  
극저온의 해수가 해저 바닥까지 닿으면 거기서부터는 바닥을 타고 흐르는데, 지나가면서 그 주변을 빙한지옥으로 만들어버린다  
해저 바닥에 살던 생물들은 그게 성게건 불가사리건 간에 영하 60도 과냉각수를 버틸 재간이 없기 때문에 그대로 바닷물과 같이 얼어죽는다  
브로니클이 죽음의 고드름이라고 불리는 이유다  

스피로그래프  

뿜  

육성 말고 모험  

무기를 빼앗고 말굽모양 자석으로 상대를 구속시킨다  

정부에서는 부족한 재정을 확충하기위해 백성에게 곡물을 받고 벼슬을 팔아 신분을 높여 주어 신분 제도에도 큰 변화가 생겼다.  

과거는 열리지 않는 '문' 과 같고, 추억은 잃어버린 '열쇠' 와 같다  

우리가 사는 우주 말고 다른 우주에서 온 충직한 전사 (자기 세계의 왕만 섬김)  

가벼운 쓰레기 버린 걸로 경찰한테 보여서 째끼다가 더 큰 사고 내면서 튀는 것 같다  

되게 무도회에서 호두깎이 인형 같은 사람이랑 공주랑 춤추는 느낌이랄까요  

여신은 눈뜨지 않습니다. 태어난 순간부터 지금가지 그리고 앞으로도 영원히 그녀는 잠들어 있습니다. 어쩌면 우리의 삶은 그녀가 꾸는 꿈일지도 모르죠.  

청춘은 젊은이에게 주기 너무 아깝다  

폼페이  

7대 금서  

동요하고 있구나 폴나레프  
아니야! 난 가요 하고있어!  

17년의 고독 50일의 우정

사람들이 나더러 노래 못한다고 말할수는 있어도, 누구도 내가 노래를 안했다고는 못할걸요  

왜 아이디어는 항상 샤워할 때 샘솟는 걸까?  
샤워를 하거나 멍 때릴 때, 즉 뇌가 외부에서 얻는 자극이 적을 때는 쉬면서 기억을 정리하는 단계로 들어가는데, 이때 일종의 재충전을 하면서 통찰력이 향상되는 효과가 있다고 한다  

실제 오아시스의 대부분은 마실 수 없는 물이라고 한다  
미생물투버 기생충, 파리때가 졸라 많고 사해처럼 졸라 짠 경우도 있다  

땃쥐  

태어나서 죽어본 적이 없다  

개밥 그릇 바뀐다고 사료임은 바뀌지 않는다  

인격을 시험하려거늘 권력을 쥐어줘봐라  

벡터리움  

남편 잃으면 과부, 아내 잃으면 홀아비, 자식 잃으면 단어조차 없음  

알라차 - 무언가인가 잘못되었음을 이상하게 여기거나 어떤 것을 신기하게 여길 때 내는 소리  
