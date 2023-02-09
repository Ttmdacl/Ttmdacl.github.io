---
title: "⛏️블렌더 애니메이션 "
date: 2023-02-06. 11:34
categories: ⛏️Memo
---

### 💎 본이 위에 보이게 하는 방법

---

본 선택 -> 초록색 졸라맨 -> Viewport Display -> In front 체크  

### 💎 본 Deform

---

본이 모델의 Weight 값을 받는지에 대한 유무  
본이 움직이면 모델도 따라서 Deform 되는지  

### 💎 애니메이션 키 프레임이 안보여

---

휠 드래그로 올려본다  
or  
View -> Frame All 을 선택하여 모든 키 프레임이 보이게 한다  

### 💎 첫 프레임으로

---

Shift + <-  

### 💎 본 팔면체에서 다른 모양으로 바꾸기

---

본 선택 -> 초록색 졸라맨 -> Viewport Display -> Display As 변경  

### 💎 회전

---

척추는 진행방향으로 조금 기울여진다 - 중심을 잡기위해  
발을 밟는 쪽으로도 조금 기울여진다  
팔을 앞뒤로 뻗을 때 어깨도 같이 기울여진다  

### 💎 키 프레임 만들기  

---

i  

### 💎 IK Len

---

0 연결된 모든 본  
1 자기 자신  
2 한 단계 위까지  

Ctrl + Page Up/Down  

### 💎 가동 범위 제한

---

Pose 모드에서,  
Bone -> Inverse Kinematics  
Lock IK -> 회전 제한  
Limit 체크 -> 회전값 제한  

Alt + R 회전 초기화  

### 💎 Auto IK

---

Tool -> Auto IK  
연결된 본들의 말단 본에 한하여 작동하는 듯  

### 💎 Color Management

---

[https://docs.blender.org/manual/en/latest/render/color_management.html](https://docs.blender.org/manual/en/latest/render/color_management.html)  

View Transform  

Filmic (Default) : Photorealistic 실사  
Standard : Non-Photorealistic  

### 💎 빛 그림자

---

Light -> Shadow  

### 💎 BSDF

---

빛과 상호작용해서 쉐이딩 결과물을 출력하는 노드  

Bidirectional Scattering Distribution Function  
빛이 재질과 어떻게 상호작용 하는지 -> BRDF + BTDF  

BRDF  
Bidirectional Reflectance Distribution Function  
빛이 어떤 방향으로 반사가 되는지  

BTDF  
Bidirectional Transmittance  Distribution Function  
빛이 어떤 방향으로 투과가 되는지  

### 💎 프레넬 효과

---

Layer Weight, Fancing  
매트하다  
Specular -> 하이라이트 영역  

### 💎 FK IK

---

Target  
Pole Target  

### 💎 MMD 모션

---

[bowlroll](https://bowlroll.net/file/204008)  
[nikoniko](https://www.nicovideo.jp/watch/sm36186539)  
