---
title: "⛏️ 메모 - 드모르간 법칙, De Morgan's Law"
date: 2023-01-09. 22:02
categories: ⛏️Memo
---

### 💎 드모르간 법칙, De Morgan's Law

---

> not (A or B) = (not A) and (not B)  
> not (A and B) = (not A) or (not B)  

```cs
// 1
if (!(file_exists && !is_protected))

// 2 (With De Morgan's Law)
if (!file_exists || is_protected)
```

2번 조건문이 더 보기 쉽다.  
