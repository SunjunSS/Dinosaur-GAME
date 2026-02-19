# 🦖 Dinosaur GAME
Windows 콘솔 환경에서 실행되는 공룡 점프 게임

<br>

## 📚 목차
- [🎯 프로젝트 개요](#-프로젝트-개요-about)
- [✨ 주요 기능](#-주요-기능-features)
- [📸 Demo](#-demo)
- [🚀 실행 방법](#-실행-방법-getting-started)

<br> 

# 🎯 프로젝트 개요 (About)
Dinosaur GAME은 Windows 콘솔 환경에서 실행되는 1인 플레이 게임입니다. <br>
장애물을 피하며 점수를 획득하고, 무적 아이템으로 더 높은 점수에 도전할 수 있습니다. 

🎮 점프/다운 조작 → 🌳 장애물 회피 → ⭐ 아이템 획득 → 🏆 고득점 도전

<br>

# ✨ 주요 기능 (Features)
- 🎮 1인 Play
- 📊 Score - 장애물 통과 시 1점씩 증가
- 🌳 장애물(나무) - 3종류, 랜덤하게 출력, 점프로 통과
- 🎨 색상 변경 - 점수 5배수마다 순서대로 색 변경
- ⭐ 아이템 - 장애물 3번 통과 시 무적 아이템 등장, 점프로 획득
- 🛡️ 무적 상태 - 아이템 획득 시 일정시간 무적, 노란색으로 변경
- ⚡ 속도 변경 - 점수 5배수마다 속도 증가 (최대속도 제한)
- ☁️ 장애물(구름) - 나무 2번 통과 시 상단 등장, 숙여서 통과
- ❌ 게임 오버 - 장애물과 충돌 시 게임 종료

<br>

## 🎮 게임 조작법

| 키 | 기능 |
|---|---|
| **Space** | 점프 |
| **↓** | 다운 (숙이기) |

<br>

# 📸 Demo

### 1. 초기화면

공룡게임 화면, 게임 시작 화면

<img width="600" alt="image" src="https://github.com/user-attachments/assets/0c7bbf3f-523b-4c88-9f3f-79731eb1fa95" />
<img width="600" alt="image" src="https://github.com/user-attachments/assets/06caa571-fae7-4815-84b2-4e747a11a917" />
<img width="600" alt="image" src="https://github.com/user-attachments/assets/747971e0-8f55-47ac-8c47-8870024d9ea7" />




### 2. 실행화면 - 장애물 등장

장애물 등장, 통과 시 score 증가 <br>
장애물(나무) 3종류가 랜덤하게 출현하며, 점프로 통과합니다. <br>
장애물(구름) 나무 2번 통과 시 화면 상단에 등장, 숙여서 통과합니다. 

<img width="600" alt="image" src="https://github.com/user-attachments/assets/cbbd0278-832d-47fe-95ba-1f251888f2a5" />
<img width="600" alt="image" src="https://github.com/user-attachments/assets/46e8a66f-29c4-4135-a143-2269da1a0eaf" />



### 3. 실행화면 - 아이템 등장

아이템 등장, 획득 시 무적<br>
장애물 3번 통과 시 무적 아이템이 등장하며, 점프로 획득 가능합니다. 

<img width="600" alt="image" src="https://github.com/user-attachments/assets/3a99cc18-bbdf-48b8-b908-7ab720308d00" />
<img width="600" alt="image" src="https://github.com/user-attachments/assets/21d14fcb-fc8a-4db8-8a1f-f8f47645d645" />



### 4. 실행화면 - 색상 변경

5배수 색 변경, 속도 증가<br>
점수가 5배수가 될 때마다 다음 순서로 색상이 변경됩니다: 
- (검은색, 초록색) → (검은색, 회색) → (검은색, 네이비) → (검은색, 보라색)

<img width="600" alt="image" src="https://github.com/user-attachments/assets/64d4c101-cf5e-47cd-9bcc-9c756dae859c" />


### 5. 실행화면 - 게임 오버

게임 오버 화면<br>
장애물과 충돌 시 게임이 종료되고 최종 점수가 표시됩니다. 

<img width="600" alt="image" src="https://github.com/user-attachments/assets/b2511e5e-9732-4e34-a311-25be649e0082" />

<br>

# 🚀 실행 방법 (Getting Started)

### 1. 사전 준비

Windows 환경에서 GCC 컴파일러 필요

**TDM-GCC 설치:**
```
https://jmeubank.github.io/tdm-gcc/download/
```

### 2. PowerShell 관리자 권한 실행

1. **PowerShell 우클릭 → "관리자 권한으로 실행"**
2. **.c 파일 위치로 이동**

```powershell
cd "파일이 있는 경로"
```

### 3. 컴파일 및 실행

```powershell
gcc 텀프로젝트.c -o 텀프로젝트.exe
.\텀프로젝트.exe
```
