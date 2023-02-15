---
title: "⛏️ Unity NavMesh"
date: 2023-02-15. 08:57
categories: ⛏️Memo
---

### 💎 Unity NavMesh

---

{% youtube 'https://youtu.be/n-RXnDGE72M' %}
<br>

[참고](https://forum.unity.com/threads/solved-problem-with-unity-navmesh-and-multiple-agent-sizes-with-a-workaround-solution.178628/)  

### 💎 Problem, Solve

---

문제 :  

여러 크기의 Agent를 사용하고 싶었는데, NavMesh는 한 번에 한 가지 크기의 Agent에 대해서만 Bake 할 수 있었다.  
때문에 Bake의 대상이 아니었던 Agent는, 해당 Agent Type의 NavMesh가 없는 곳에 배치되어 'Failed to create agent because it is not close enough to the NavMesh' 에러 로그를 뿜어냈다.  

여러 Agent Type에 대해, NavMesh를 '각각' Bake 하는 방법이 필요했다.  

---

해결 :  

NavMesh Building Components 중 NavMeshSurface 컴포넌트를 이용하면, 여러 Agent Type에 대해 NavMesh를 '각각' 구워낼 수 있다.  

NavMesh Building Components는 AI Navigation 패키지의 Experimental 버전에서 지원되고 있다. (23-02-15 기준)  
Unity 2021 기본 NavMesh 에는 이 컴포넌트들이 내장되어 있지 않다.  
때문에 따로 패키지를 설치해줘야 한다.  

패키지 설치는 [Unity NavMesh Building Components](https://docs.unity3d.com/2021.3/Documentation/Manual/NavMesh-BuildingComponents.html) 문서를 참고했다.  

사용 방법은, 이 글 맨 위에 링크한 [Unite Europe 2017 - Finding the path: New navigation features](https://youtu.be/n-RXnDGE72M?t=180) 강연을 참고했다. (3분 부터 해당 내용이 나온다.)  
