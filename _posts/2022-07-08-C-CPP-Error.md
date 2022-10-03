---
title: C / C++ 에러
date: 2022-07-08. 13:54
categories: Programming Programming-Normal
tags: C CPP
---

> [C++ C3861](https://docs.microsoft.com/ko-kr/cpp/error-messages/compiler-errors-2/compiler-error-c3861?view=msvc-170)  
> 에러 : '뭐시깽' 식별자를 찾을 수 없습니다.  
> 해결 : 함수 위치 밑 선언 확인  

> [C++ C2360](https://docs.microsoft.com/ko-kr/cpp/error-messages/compiler-errors-1/compiler-error-c2360?view=msvc-170), [C++ C2361](https://docs.microsoft.com/ko-kr/cpp/error-messages/compiler-errors-1/compiler-error-c2361?view=msvc-170)  
> 에러 : '뭐시깽' 초기화가 'case'/'default' 레이블에 의해 생략되었습니다.  
> 해결 : 변수 선언하는 case에 스코프 {} 달아주기  
> [설명](https://ansohxxn.github.io/cpp/chapter5-1/) : case/default 이전 공간에서는 메모리 할당 안됨