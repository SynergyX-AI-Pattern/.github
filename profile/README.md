# 📈 PatternCatcher (패턴캐처) 
**🏆 한이음 드림업 장려상 수상작**

> **사용자 정의 차트 패턴 기반 실시간 감지·백테스팅·AI 투자 보조 시스템**

[![Demo](https://img.shields.io/badge/데모_영상-C93B47?style=for-the-badge&logo=youtube&logoColor=white)](https://youtu.be/KmI5lIBw4qw)
[![Presentation](https://img.shields.io/badge/발표_자료-6C94D4?style=for-the-badge&logo=googledocs&logoColor=white)](https://github.com/user-attachments/files/23898620/PatternCatcher.pdf)

<img width="4800" height="2400" alt="1-6f60498e" src="https://github.com/user-attachments/assets/24c17eaf-4506-4365-9752-37737730047c" />

---

## 📌 프로젝트 개요

PatternCatcher는 **나만의 투자 전략을 만들고 싶은 투자자**를 위해,  
사용자 정의 차트 패턴 기반 실시간 감지·백테스팅·AI 분석을 제공하는 **AI 투자 보조 시스템**입니다.

<br/>

<table>
  <tr>
    <td align="center" width="25%">
      <img src="https://github.com/user-attachments/assets/67e003b8-f02b-4bb4-b1e5-b75596e0abc4" width="100%"/>
      <br />
      <b>📍 실시간 패턴 감지</b>
      <br />
      <sub>DTW 알고리즘 기반<br/>평균 유사도 0.85</sub>
    </td>
    <td align="center" width="25%">
      <img src="https://github.com/user-attachments/assets/cbb50423-2795-44de-a1bf-81d25df814bd" width="100%"/>
      <br />
      <b>📊 패턴 백테스팅</b>
      <br />
      <sub>과거 5년 데이터<br/>수익률 검증</sub>
    </td>
    <td align="center" width="25%">
      <img src="https://github.com/user-attachments/assets/d92c5158-1a42-4097-bb2b-b87c786944d6" width="100%"/>
      <br />
      <b>🤖 AI 주가 예측</b>
      <br />
      <sub>GRU 모델 기반<br/>MAPE 2.96%</sub>
    </td>
    <td align="center" width="25%">
      <img src="https://github.com/user-attachments/assets/131b430f-96af-4516-8487-519e0f554250" width="100%"/>
      <br />
      <b>💭 AI 감정 투자 일기</b>
      <br />
      <sub>GPT-4o 기반<br/>투자 조언 제공</sub>
    </td>
  </tr>
</table>

<br/>

### ✨ 프로젝트 특징
1. **DTW 기반 패턴 분석**: 시계열 정규화와 유사도 계산으로 평균 0.85 정확도 달성
2. **효율적 백테스팅**: 슬라이딩 윈도우·이진 탐색으로 5년 데이터 고속 분석
3. **AI 융합 시스템**: Vision AI·GPT-4o·GRU 모델을 통합한 다각도 투자 분석
4. **직관적 UX**: 복잡한 금융 데이터를 시각화하여 누구나 쉽게 전략 설계 가능

<br/>

### 🚀 기대효과 및 활용분야

**기대효과**
- AI 분석을 활용한 투자 효율성 및 전략 판단의 신뢰성 향상
- 개인 투자자의 전략적 의사결정 능력 및 시장 대응력 강화

**활용분야**
- 개인 투자자와 금융 리서치 기업의 전략 검증·분석 도구로 활용
- 투자 교육 및 알고리즘 트레이딩 학습용 실습 플랫폼에 적용

---

## 🛠 Tech Stack
| **Backend** | **ML/AI** | **Frontend** | **Database** | **Infrastructure** | **External API** |
|-------------|-----------|--------------|--------------|-------------------|------------------|
| ![Java](https://img.shields.io/badge/Java-17-007396?logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.4.4-6DB33F?logo=springboot&logoColor=white) ![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?logo=springsecurity&logoColor=white) | ![Python](https://img.shields.io/badge/Python-3.12-3776AB?logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white) | ![Flutter](https://img.shields.io/badge/Flutter-3.7.2-02569B?logo=flutter&logoColor=white) ![Dart](https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=white) | ![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?logo=mysql&logoColor=white) | ![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?logo=amazonec2&logoColor=white) ![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?logo=amazons3&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black) | ![한국투자증권](https://img.shields.io/badge/한국투자증권_API-003876?logo=investopedia&logoColor=white) ![Google Vision AI](https://img.shields.io/badge/Vision_AI-4285F4?logo=google&logoColor=white) ![GPT-4o](https://img.shields.io/badge/GPT--4o-412991?logo=openai&logoColor=white) |

---

## 🏗 System Architecture
<img width="579" alt="스크린샷 2025-12-01 22 46 30" src="https://github.com/user-attachments/assets/f7ae2bbf-5c16-4480-94c4-e54c5ca0359a" />

---

## 📂 Repository 구조

### [📘 Main Server](https://github.com/SynergyX-AI-Pattern/SynergyX-Server)
Spring Boot 기반 RESTful API 서버 (인증, 종목 관리, 패턴 CRUD, FCM 알림)

### [📗 ML Server](https://github.com/SynergyX-AI-Pattern/SynergyX-ML-Server)
FastAPI 기반 AI/ML 서버 (DTW 패턴 감지, GRU 예측, GPT/Vision AI 연동)

### [📙 Client](https://github.com/SynergyX-AI-Pattern/SynergyX-Client)
Flutter 기반 크로스 플랫폼 모바일 앱 (Android/iOS)

---

## 💾 Database Schema (ERD)
<img width="2868" height="1373" alt="PatternCatcher ERD v4" src="https://github.com/user-attachments/assets/886f1424-93fe-4d88-a384-a7e9a6786d1d" />

---
## 🚀 주요 기능

### 1. 사용자 정의 차트 패턴 실시간 감지
- **패턴 등록**: 드래그 앤 드롭 방식으로 직관적인 패턴 생성
- **실시간 감지**: DTW 알고리즘 기반 패턴 매칭 (평균 유사도 **0.85**)
- **즉시 알림**: FCM 푸시 알림으로 매칭 시점 즉시 전달 (성공률 **99%**)

### 2. 패턴 백테스팅
- **과거 데이터 검증**: 최근 5년(2020~2025) 거래 데이터 분석
- **수익률 분석**: 평균/최대/최소 수익률, 승률, 누적 수익률 제공
- **전략 비교**: 백테스팅 랭킹으로 사용자 간 전략 비교

### 3. AI 종목 검색
- **이미지 인식**: Vision AI로 제품·로고·매장 사진에서 종목 추출
- **종목 추론**: GPT-4o 기반 상장 여부 자동 판별 및 종목 매칭

### 4. AI 감정 투자 일기
- **감정 분석**: GPT-4o로 투자 일기의 감정 키워드 추출
- **투자 조언**: 감정 상태 기반 맞춤형 투자 가이드 제공

### 5. AI 주가 예측
- **GRU 모델**: 최근 5년 데이터 학습, 향후 15일 종가 예측
- **높은 정확도**: MAPE **2.96%**, ±5% 이내 예측률 **82.9%**
- **매매 신호**: 예측 기반 매수/매도 추천

---

## 📱 화면 구성

<table>
  <tr>
    <td align="center" width="25%">
      <img src="https://github.com/user-attachments/assets/28e9e6d1-2417-4314-96f1-9da0d3be5baf" width="100%"/>
      <br />
      <sub><b>홈 화면</b></sub>
      <br />
      <sub>Top 20 / AI Top 20</sub>
    </td>
    <td align="center" width="25%">
      <img src="https://github.com/user-attachments/assets/67e003b8-f02b-4bb4-b1e5-b75596e0abc4" width="100%"/>
      <br />
      <sub><b>종목 상세</b></sub>
      <br />
      <sub>차트 / AI 예측</sub>
    </td>
    <td align="center" width="25%">
      <img src="https://github.com/user-attachments/assets/73670a7e-1a1a-4f67-bfba-7cc0ba68999e" width="100%"/>
      <br />
      <sub><b>패턴 생성</b></sub>
      <br />
      <sub>드래그 방식</sub>
    </td>
    <td align="center" width="25%">
      <img src="https://github.com/user-attachments/assets/cbb50423-2795-44de-a1bf-81d25df814bd" width="100%"/>
      <br />
      <sub><b>백테스팅 결과</b></sub>
      <br />
      <sub>수익률 분석</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="25%">
      <img src="https://github.com/user-attachments/assets/2fcdd623-6705-4982-907e-e120999a86a6" width="100%"/>
      <br />
      <sub><b>AI 종목 검색</b></sub>
      <br />
      <sub>이미지 기반</sub>
    </td>
    <td align="center" width="25%">
      <img src="https://github.com/user-attachments/assets/131b430f-96af-4516-8487-519e0f554250" width="100%"/>
      <br />
      <sub><b>감정 투자 일기</b></sub>
      <br />
      <sub>AI 분석</sub>
    </td>
    <td align="center" width="25%">
      <img src="https://github.com/user-attachments/assets/f1d5bcd7-c144-44d9-b380-43d0a64434dc" width="100%"/>
      <br />
      <sub><b>관심 종목</b></sub>
      <br />
      <sub>종목 관리</sub>
    </td>
    <td align="center" width="25%">
      <img src="https://github.com/user-attachments/assets/f800212a-5512-4d59-9633-5f79ac07a07b" width="100%"/>
      <br />
      <sub><b>관심 종목</b></sub>
      <br />
      <sub>종목 관리</sub>
    </td>
  </tr>
</table>

---

## 📊 프로젝트 성과

### 🏆 수상
- **한이음 드림업 장려상** 수상

### 📈 정량적 성과
- 패턴 감지 정확도: DTW 유사도 평균 **0.85**
- 예측 오차율: MAPE **2.96%**
- 예측 안정성: NRMSE **8.83%**
- 알림 성공률: **99.0%**
- ±5% 이내 예측: **82.9%**

### 👥 사용자 평가
설문조사 결과 (5점 만점):
- 패턴 등록·백테스팅 기능: **4.6점**
- AI 종목 검색·감정 분석: **4.5점**

**주요 피드백**
- "패턴 감지를 통한 매매 타이밍 파악이 유용함"
- "AI 종목 검색이 흥미롭고 접근성이 높음"
- "백테스팅 결과가 투자 전략 수립에 도움됨"

---

## 👥 Team

### Frontend ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white) ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white)

| 이가현 | 이채원 |
|:------:|:------:|
| <img width="160px" src="https://avatars.githubusercontent.com/KaHeyon" /> | <img width="160px" src="https://avatars.githubusercontent.com/Chaewon5227" /> |
| [@KaHeyon](https://github.com/KaHeyon) | [@Chaewon5227](https://github.com/Chaewon5227) |
| **Frontend · Design Lead** | **Frontend · Design** |

### Backend ![SpringBoot](https://img.shields.io/badge/SpringBoot-6DB33F?style=flat&logo=springboot&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

| 한지수 | 조수민 |
|:------:|:------:|
| <img width="160px" src="https://avatars.githubusercontent.com/eldeoddt" /> | <img width="160px" src="https://avatars.githubusercontent.com/Soomxn" /> |
| [@eldeoddt](https://github.com/eldeoddt) | [@Soomxn](https://github.com/Soomxn) |
| **Team Lead · Backend** | **Backend · ML Engineer** |

---

## 🔗 Related Links

### Repositories
- [📘 Main Server](https://github.com/SynergyX-AI-Pattern/SynergyX-Server)
- [📗 ML Server](https://github.com/SynergyX-AI-Pattern/SynergyX-ML-Server)
- [📙 Client](https://github.com/SynergyX-AI-Pattern/SynergyX-Client)

### Documentation
- [📄 발표 자료](https://github.com/user-attachments/files/23898620/PatternCatcher.pdf)

### Demo
- [🎥 데모 영상](https://youtu.be/KmI5lIBw4qw)

---

## 📧 Contact
- **Email**: patterncatcher83@gmail.com
---

<div align="center">

**PatternCatcher** by Team SynergyX

*사용자 정의 차트 패턴 기반 실시간 감지·백테스팅 시스템*

© 2025 Team SynergyX

</div>
