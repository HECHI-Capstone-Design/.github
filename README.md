<div align="center">
  <img width="350" alt="HECHI Logo" src="https://github.com/user-attachments/assets/9ec25181-55cc-471b-a34c-1e50eb93da8d" />
  
  <h1>HECHI -
    종이책 X 디지털 : 하이브리드 독서 경험 서비스
  </p>
  </h1>
</div>



## 💡 서비스 소개
**HECHI**는 종이책의 몰입감은 유지하면서  
전자책의 편리한 독서 관리 기능을 결합한  
**하드웨어 + 모바일 애플리케이션 기반 독서 기록 서비스**입니다.



## 🔍 프로젝트 한눈에 보기

- 📖 종이책 독서 **자동 기록**
- 🔌 BookStopper 하드웨어 연동
- 📱 HECHI 모바일 애플리케이션
- 📊 독서 데이터 분석 및 시각화
- 🧠 독서 습관 형성 및 동기 부여



## 🎯 프로젝트 배경

전자책은 독서 시간, 진도율, 하이라이트 등  
데이터 기반 관리 기능을 제공하지만  
DRM 제한, 네트워크 의존성, 화면 피로도라는 한계를 가지고 있습니다.

반면 종이책은 높은 몰입감과 학습 효과를 제공하지만  
독서 기록과 분석이 어렵다는 구조적인 한계가 존재합니다.

**HECHI는 이 두 독서 환경의 장점을 결합**하여  
종이책 독서 경험을 해치지 않으면서도  
자동 기록이 가능한 새로운 독서 경험을 제공합니다.



## 💡 핵심 아이디어

> **“종이책 독서 행동을 디지털 데이터로 변환하자”**

- 페이지 넘김, 책 열고 닫는 행동을 하드웨어로 감지
- 독서 데이터를 자동으로 모바일 앱에 기록
- 수동 입력 없이 체계적인 독서 관리 가능


## 🧱 시스템 구성

### 1️⃣ BookStopper (하드웨어)

- 종이책 측면 부착형 디바이스
- 페이지 이동 / 독서 시작 · 종료 감지
- BLE(Bluetooth Low Energy) 기반 통신
- 저전력 설계로 장시간 사용 가능



### 2️⃣ HECHI 모바일 애플리케이션

- BookStopper 데이터 실시간 수신
- 독서 세션 단위 기록 저장
- 독서 데이터 분석 및 시각화 제공



## 🏗 시스템 아키텍처

<img width="1968" height="934" alt="HECHI Architecture" src="https://github.com/user-attachments/assets/2caa7ca8-bc92-4d10-a09f-0e4f3123aa3a" />



## 📱 화면 구성 (Screen Flow)

### 🔐 로그인 & 초기 설정
- 로그인 / 회원가입
- 독서 목적 및 선호 장르 설정



### 🏠 홈 화면
- 현재 읽는 도서
- 누적 독서 시간
- 주요 독서 지표 요약



### 📚 도서 보관함
- 읽는 중 / 완독 / 위시리스트 관리
- 도서 상태별 필터 제공



### 📖 독서 상세 화면
- 페이지 수 및 진행률 표시
- 독서 시간 자동 기록
- 북마크 / 하이라이트 / 메모 관리



### 📊 독서 분석 화면
- 일 · 주 · 월 독서 통계
- 페이지 수 · 완독률 시각화
- 캘린더 기반 독서 기록



## 📱 주요 기능

- ISBN 기반 도서 등록
- 종이책 독서 자동 기록
- 독서 세션 단위 관리
- 📚 독서 보관함  
  - 북마크 / 하이라이트 / 메모 관리
- 📊 일 · 주 · 월 독서 통계 제공
- 🏆 독서 성취 기반 동기 부여



## 🧪 테스트 및 검증

- BLE 통신 안정성 테스트
- 페이지 카운트 정확도 검증
- 독서 시간 기록 오차 비교

👉 실제 독서 환경에서도 **안정적인 동작** 확인



## 👥 Team HECHI

| 프로필                                                      | 이름      | 역할                                  |
| -------------------------------------------------------- | ------- | ----------------------------------- |
| <img src="https://github.com/sunmer79.png" width="60"/>  | **강여름** | PM · Frontend · Mobile App · Design |
| <img src="https://github.com/username2.png" width="60"/> | **조성현** | Frontend · Mobile App · Design      |
| <img src="https://github.com/username3.png" width="60"/> | **김효림** | Backend · Server                    |
| <img src="https://github.com/username4.png" width="60"/> | **백새빈** | Frontend · Mobile App · Design      |
| <img src="https://github.com/SUB1023.png" width="60"/> | **손유빈** | Backend · Hardware                  |
| <img src="https://github.com/dalhye.png" width="60"/> | **김달해** | Frontend · Mobile App · Design      |

> 캡스톤 디자인 프로젝트  
> Hardware × Software 융합 팀 **HECHI**


## 📂 Repository

| 파트                           | GitHub 링크                                                                                                          |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| 🖥 **Backend**               | [https://github.com/HECHI-Capstone-Design/HECHI-BE](https://github.com/HECHI-Capstone-Design/HECHI-BE)   |
| 📱 **Frontend (Mobile App)** | [https://github.com/HECHI-Capstone-Design/HECHI-FE](https://github.com/HECHI-Capstone-Design/HECHI-FE) |



