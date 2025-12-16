# Python Console Poker Game
```
PokerProject/               <-- (최상위 폴더)
│
├── 📂 src/                 <-- (새 폴더 만들기, 이름: src)
│   └── 📄 poker_game.py    <-- (이 안에 파이썬 파일 생성)
│
├── 📄 .gitignore           <-- (메모장으로 만들고 확장자 지우기)
└── 📄 README.md            <-- (메모장으로 만들고 이름 변경)
<div align="center">
```  
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Project-Term%20Paper-blueviolet?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge">
  
  <br>
  <br>
  
  **"순수 파이썬으로 구현한, 텍스트 포커 게임"**
  <br>
  외부 라이브러리 없이 객체 지향(OOP) 설계와 파일 입출력(I/O)을 완벽하게 구현했습니다.

</div>

<br>

## 프로젝트 개요 (Project Info)

| 개발자 | 양수 |
|핵심 기술| OOP 설계, File I/O(로그 저장), ANSI Color UI |

<br>

## 💡 핵심 기능 (Key Features)

이 프로그램은 단순한 텍스트 출력을 넘어, **사용자 경험(UX)**을 고려한 디테일한 기능을 제공합니다.

### 1. 직관적인 컬러 UI (Colorful Interface)
> 터미널 환경에서도 카드의 색상을 구분하여 가독성을 극대화했습니다.
- **RED Card (♥️, ♦️):** 붉은색 텍스트로 강조
- **BLUE Card (♠️, ♣️):** 푸른색 텍스트로 강조
- **Status:** 승리/패배/파산 등 상태에 따른 색상 변화

### 2. 독자적 족보 알고리즘 (Custom Algorithm)
> `RuleMaster` 클래스를 통해 포커의 복잡한 승패 로직을 직접 구현했습니다.
- **Supported Hands:** 스트레이트 플러시, 포카드, 풀하우스, 플러시, 스트레이트, 트리플, 투페어, 원페어, 하이카드
- 외부 라이브러리(`collections` 등) 의존 없이 **순수 로직**으로 구현

### 💾 3. 자동 기록 시스템 (Auto-Logging)
> 게임의 모든 결과는 영구적으로 기록됩니다. `JSON` 대신 텍스트 입출력을 직접 제어합니다.
- **Log Path:** `./game_records/history.txt` (자동 생성)
- **Content:** 승자, 획득 금액, 잔액, 타임스탬프 기록

<br>

## 🚀 시작 가이드 (Getting Started)

별도의 라이브러리 설치(`pip install`)가 필요 없습니다. 소스 코드를 다운로드하고 바로 실행하세요.

### 1. 실행 방법
프로젝트 폴더(루트 경로)에서 아래 명령어를 입력합니다.

```bash
python src/poker_game.py
![화면 캡처 2025-12-16 185520](https://github.com/user-attachments/assets/9c0cdec7-3717-48c5-95c3-08e74ed46682)
![화면 캡처 2025-12-16 185427](https://github.com/user-attachments/assets/83158d57-1278-4e0b-a2f8-0007a76cc4bd)
