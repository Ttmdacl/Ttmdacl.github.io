---
title: "Instruction Cycle"
date: 2022-10-05. 09:42
categories: Programming Programming-Normal
---

CPU 명령어 사이클 (instruction cycle, 인스트럭션 사이클)

5-0.
마이크로프로세서가 메모리로부터 프로그램 된 한 개의 기계어 명령어를 가져와 어떠한 동작을 요구하는지를 결정하고 명령어가 요구하는 동작을 수행하는 연속적인 동작 과정

= 즉, 명령어를 꺼내와 실행하기 위한 연속적인 동작 과정

5-1. 사용되는 회로

- PC : 다음에 실행할 명령어에 대한 메모리 주소를 추적
- MAR : 다음에 실행할 명령어의 메모리에 있는 주소를 보관
- MBR : 메모리로부터 페치(fetch)되어 cpu가 처리할 준비가 된 데이터나 메모리에 저장되어 대기 중인 데이터를 보관하는 양방향 레지스터
- IR : 메모리로부터 fetch 되는 (현재 실행할) 명령어를 일시적으로 보관하는 영역
- CU : 명령어 인출, 해독, 실행을 위한 제어신호를 타이밍에 맞춰 발생시킨다.
- ALU : 산술 및 논리 연산을 수행

5-2. 명령어 기본 사이클

- CPU에서 명령어를 읽어오는 단계

5-2-1. 명령어 인출 사이클 (instruction fectch 사이클)

- CPu에서 명령어를 실행하는 단계

[참고](https://gamedevlog.tistory.com/71)