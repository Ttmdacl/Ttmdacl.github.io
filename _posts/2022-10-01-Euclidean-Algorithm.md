---
title: 유클리드 호제법
date: 2022-10-01. 08:42
categories: Programming Normal
---

최대공약수를 구하는 알고리즘

A를 B로 나눈 나머지 r (이때, A > B)  
A와 B의 최대 공약수는 B와 r의 최대 공약수

```cs
// 보통 최대공약수 Greatest Common Divisor : GCD 라고 함수 이름 짓는 듯

// 최소공배수 Least/Lowest Common Multiple : LCM
// 최대공약수를 알면 최소공배수도 구할 수 있음 (A * B = GCD * LCM)

// a = A / GCD;
// b = B / GCD;
// LCM = GCD * a * b;
// A * B = GCD * (GCD * a * b);
// A * B = GCD + LCM

// int [] { 최대공약수, 최소공배수 } 반환
public int[] GCD(int A, int B)
{
    // A % B, 최종적으로 GCD가 됨
    int r = 0;

    while (A % B != 0)
    {
        r = A % B;
        A = B;
        B = r;
    }

    return r == 0 
    ? new int[] { A, B } 
    : new int[] { r, A * B / r };
}

// 참고 : CPP STL 내장 함수로도 존재 gcd, lcm
```
