---
title: "To Study - Shader, Unity"
date: 2022-10-17. 14:42
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
