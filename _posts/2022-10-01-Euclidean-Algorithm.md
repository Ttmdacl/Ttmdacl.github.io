---
title: 유클리드 알고리즘/호제법
date: 2022-10-01. 08:42
categories: Programming Algorithm
tags: Algorihtm
use_math: true
---

A를 B로 나눈 나머지 r (이때, A > B)  
A와 B의 최대공약수는 B와 r의 최대공약수와 같음을 이용하여 A와 B의 최대공약수를 구하는 알고리즘  

참고 : 최대공약수를 알면 최소공배수도 구할 수 있음  

a = A / GCD  
b = B / GCD  
LCM = GCD * a * b  
A * B = GCD * a * GCD * b  
A * B = GCD * LCM  

CPP STL 내장 함수로도 존재 gcd, lcm 

최대공약수 GCD Greatest Common Divisor  
최소공배수 LCM Least/Lowest Common Multiple  

```cs
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

```

---

## 약수 ([約](https://hanja.dict.naver.com/#/entry/ccko/ecc0d50d850b485a8361cb39d3995490){: target="_blank"}-, Divisor) | 인수 ([因](https://hanja.dict.naver.com/#/entry/ccko/cec202238f684acf86d21bf343b79aa8){: target="_blank"}-, Factor)  

---

[묶여있는](https://hanja.dict.naver.com/#/entry/ccko/ecc0d50d850b485a8361cb39d3995490){: target="_blank"} 수  
[원인, 원소, 이유가 되는](https://hanja.dict.naver.com/#/entry/ccko/cec202238f684acf86d21bf343b79aa8){: target="_blank"} 수  

(A, B ∈ ℕ), A ≠ 0 일 때,  
A가 B의 약수 ⇔ B = A * k (k ∈ ℕ)  
A가 B의 약수 ⇔ A가 B를 나눈다 ⇔ A|B  

## 공약수, Common Divisor (Factor)  

---
A, B의 공통된 약수  

## 최대공약수, GCD, Greatest Common Divisor (Factor)  

---
A, B 의 공약수 중에서 가장 큰 수  
gcd(A, B) ⇔ A, B의 최대공약수  

## 서로소 (-[素](https://hanja.dict.naver.com/#/entry/ccko/d16e6665e5f943be80491da2e2d0f3d4){: target="_blank"}, Coprime)

---

[서로 묶이지 않는](https://hanja.dict.naver.com/#/entry/ccko/d16e6665e5f943be80491da2e2d0f3d4){: target="_blank"} 수, [서로가 순수한(공통이 없는 수)](https://hanja.dict.naver.com/#/entry/ccko/d16e6665e5f943be80491da2e2d0f3d4){: target="_blank"} 수  

A, B가 서로소다 ⇔ 공약수(최대공약수)가 1이다 ⇔ 1을 제외한 공약수가 없다 ⇔ 공약수의 개수가 1개이다  
gcd(A, B) = 1  

## 유클리드 알고리즘/호제법  

---

(A, B, r ∈ ℕ), (0 ≤ r ＜ B ＜ A) 일 때,  
gcd(A, B) ⇔ gcd(B, r)  
A = qB + r ⇔ B = qr + r₂  

pf )  
assume gcd(A, B) = g, gcd(B, r) = g  
  
A = ga, B = gb  
a, b는 서로소 ⇔ gcd(a, b) = 1 (∵ if gcd(a, b) = k ⇔ k|A, k|B ⇔ gcd(A, B) = gk ≠ gcd(A, B) = g)  

A = qB + r ⇔ ga = qgb + r (∵ A = ga, B = gb)  
r = ga - qgb = g(a - qb)  
∴ g|r  

α ≔ (a - qb)  
r = gα  

gcd(B, r) = g 를 증명하기 위해서  
B = gb, r = gα 를 가지고  
gcd(b, α) = 1 을 증명해보자 (∵ if gcd(b, α) = k ⇔ k|B, k|r ⇔ gcd(B, r) = gk ≠ gcd(B, r) = g)  

귀류법  
gcd(b, α) = k 이라면?  

A = qB + r ⇔ ga = qgb + gα (∵ A = ga, B = gb, r = gα)  
b = kβ, α = kγ  
gcd(β, γ) = 1 (∵ gcd(b, α) = k)  

A = ga = qgkβ + gkγ = gk(qβ + γ)  
∴ gk | A  
B = gb = gkb  
∴ gk | B  
이러면 A, B의 최대공약수가 gk 이므로 gcd(A, B) = g 와 모순

∴ gcd(β, γ) ≠ 1, gcd(b, α) ≠ k  
∴ gcd(b, α) = 1  
∴ gcd(B, r) = g  
∴ gcd(A, B) = gcd(B, r)  

이를 통해 큰 수 (A, B) 를 작은 수 (B, r) 로 계산할 수 있다.  
