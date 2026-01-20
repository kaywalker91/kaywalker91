# 김대각 | 4년차 Flutter 모바일 앱 개발자
> Kim Daegak | Flutter Mobile App Developer with 4 Years Experience

<div align="center">
  <a href="https://github.com/kaywalker91">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&duration=3000&pause=1000&color=02569B&center=true&vCenter=true&multiline=true&width=700&height=100&lines=4%EB%85%84%EC%B0%A8+Flutter+%EA%B0%9C%EB%B0%9C%EC%9E%90;Clean+Architecture+%26+Riverpod;100M%2B+Downloads+%7C+Web3+%26+DeFi" alt="Typing SVG" />
  </a>

  <!-- 주요 성과 뱃지 -->
  <p>
    <img src="https://img.shields.io/badge/다운로드-1억+-success?style=for-the-badge&labelColor=2B2B2B" alt="1억+ 다운로드"/>
    <img src="https://img.shields.io/badge/Flutter-3년_4개월-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter 3년 4개월"/>
    <img src="https://img.shields.io/badge/Web3-WalletConnect_v2-3B99FC?style=for-the-badge&logo=walletconnect&logoColor=white" alt="WalletConnect v2"/>
  </p>

  <img src="https://komarev.com/ghpvc/?username=kaywalker91&color=02569B&style=flat-square&label=Profile+Views" alt="Profile views" />
</div>

---

## 소개 | About Me

> **"안정성과 완성도를 중시하는 개발자"**

- 현재 **㈜포롱(FORLONG)**에서 **iLity Hub** 개발 중 - 멀티체인 크립토 지갑 & 소셜 트레이딩 플랫폼
- 정부 재난안전 앱 Flutter 전환 담당 (**1억+ 다운로드**)
- **Clean Architecture**, **Riverpod 3.x**, **WalletConnect v2** 전문
- AI 활용 개발: Claude Code, Cursor AI, Gemini (생산성 30% 향상)

---

## 주요 프로젝트 | Featured Projects

### 1. iLity Hub - 멀티체인 Web3 지갑 `현재 진행중`
> 멀티체인 크립토 지갑 & 소셜 트레이딩 플랫폼

| 기술 스택 | 주요 기능 |
|----------|----------|
| Flutter, Riverpod 3.x, Clean Architecture | EVM 네트워크 (Ethereum, BNB Chain, Base) |
| WalletConnect v2, reown_appkit | 8종 지갑 지원 (MetaMask, Trust Wallet 등) |
| fl_chart, DeFi Integration | Swap/Bridge/Liquidity Pool UI |

**핵심 성과:**
- 50,000+ LOC, 12개 모듈, 86개 Provider
- State Machine 기반 4단계 지갑 연결 플로우
- 온체인 트랜잭션 검증 기반 Trustless Social Feed
- 299개 테스트 케이스 (33.47% 커버리지)

---

### 2. 안전디딤돌 (Emergency Ready App) `1억+ 다운로드`
> 행정안전부 공식 재난안전 서비스앱

| 기술 스택 | 주요 기능 |
|----------|----------|
| Flutter, Riverpod, MVVM/Repository | 실시간 재난 알림 |
| Firebase FCM, Hive, Google Translate API V3 | 19개국 다국어 번역 |
| Flutter TTS, Semantics | TalkBack/VoiceOver 접근성 |

**핵심 성과:**
- Android/iOS 레거시(Java/Objective-C) → Flutter 100% 마이그레이션
- `LocationBasedFCMManager`: 위치 기반 자동 구독/해제
- `RegionStabilityChecker`: GPS 오차 보정 (3회 검증 / 30초 주기)
- Priority Queue 기반 긴급 메시지 전달

---

### 3. MindLog - AI 감정 다이어리 `Production`
> Llama 3.3 기반 스마트 감정 분석 다이어리

| 기술 스택 | 주요 기능 |
|----------|----------|
| Flutter, Groq API (Llama 3.3) | 감정 분석 & 맞춤형 위로 메시지 |
| Firebase, fl_chart | 감정 추이 시각화 |
| Local-First Pattern | 네트워크 요청 전 데이터 저장 |

**핵심 성과:**
- 4가지 상태별 오버레이 UI (5~10초 AI 분석 대기 시간)
- 2단계 안전 필터 (입력 키워드 + AI 응답 검증)
- 위기 상황 감지 시 상담 전화 즉시 연결
- Google Play Store v1.4.2 - 6회 업데이트

[![MindLog](https://img.shields.io/badge/Google_Play-MindLog-414141?style=for-the-badge&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.kaywalker.mindlog)

---

### 4. Crypto Wallet Pro `학습 프로젝트`
> WalletConnect v2 프로토콜 학습 & 멀티체인 지갑 프로토타입

- MetaMask, Trust Wallet 등 8종 지갑 지원
- Ethereum, BNB Chain, Base EVM 네트워크 통합
- Android 백그라운드 WebSocket 재연결: Exponential Backoff & Optimistic Session Check

[![Crypto-Wallet-Pro](https://img.shields.io/badge/GitHub-Crypto--Wallet--Pro-181717?style=for-the-badge&logo=github)](https://github.com/kaywalker91/Crypto-Wallet-Pro)

---

### 5. TimeWalker - 인터랙티브 역사 교육 게임 `Personal Project`
> 시간 여행과 지도 탐험을 결합한 역사 교육 어드벤처

| 기술 스택 | 주요 기능 |
|----------|----------|
| Flutter, Flame Engine | 월드맵 탐험 및 시대별 여행 |
| Riverpod 3.x, Supabase | 역사 인물과 분기형 대화 시스템 |
| Offline-First Pattern | 백과사전/퀴즈 기반 다층적 학습 |

**핵심 기능:**
- Flame 엔진 기반 월드맵 인터랙션
- 역사 인물과의 분기형 대화 시스템
- Supabase 클라우드 동기화 + 오프라인 캐싱

[![TimeWalker](https://img.shields.io/badge/GitHub-TimeWalker-181717?style=for-the-badge&logo=github)](https://github.com/kaywalker91/TimeWalker)
[![Live Demo](https://img.shields.io/badge/Live-Demo-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://kaywalker91.github.io/TimeWalker/)

---

## 기술 스택 | Tech Stack

### 전문 분야 | Expert
<p>
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter"/>
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" alt="Dart"/>
  <img src="https://img.shields.io/badge/Riverpod_3.x-00758F?style=for-the-badge&logo=dart&logoColor=white" alt="Riverpod"/>
  <img src="https://img.shields.io/badge/Clean_Architecture-6DB33F?style=for-the-badge" alt="Clean Architecture"/>
</p>

### 숙련 분야 | Advanced
<p>
  <img src="https://img.shields.io/badge/Web3.js-F16822?style=for-the-badge&logo=web3dotjs&logoColor=white" alt="Web3"/>
  <img src="https://img.shields.io/badge/WalletConnect-3B99FC?style=for-the-badge&logo=walletconnect&logoColor=white" alt="WalletConnect"/>
  <img src="https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=ethereum&logoColor=white" alt="Ethereum"/>
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase"/>
  <img src="https://img.shields.io/badge/Hive-FF7043?style=for-the-badge" alt="Hive"/>
</p>

### 경험 분야 | Proficient
<p>
  <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android"/>
  <img src="https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=ios&logoColor=white" alt="iOS"/>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/>
  <img src="https://img.shields.io/badge/Swift-F54A2A?style=for-the-badge&logo=swift&logoColor=white" alt="Swift"/>
  <img src="https://img.shields.io/badge/RxJava-B7178C?style=for-the-badge&logo=reactivex&logoColor=white" alt="RxJava"/>
</p>

### 도구 & 데이터베이스 | Tools & Database
<p>
  <img src="https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS"/>
</p>

---

## 경력 타임라인 | Career Timeline

```
2025.12 ─── ㈜포롱 (FORLONG) | iLity Hub 멀티체인 지갑 (현재)
    │       50,000+ LOC, 12개 모듈, 299개 테스트 케이스
    │
2024.11 ─── ㈜시선아이티 | 안전디딤돌 Flutter 전환 (1억+ 다운로드)
    │       19개국 다국어 지원, 레거시→Flutter 100% 마이그레이션
    │
2022.10 ─── ㈜플레이스링크 | 포인트투어 위치기반 앱
    │       앱 다운로드 400% 증가, 대전시 "0시축제" B2G 프로젝트
    │
2022.04 ─── DW 아카데미 | 스마트 웹&앱 개발 과정
```

---

## GitHub 통계 | GitHub Stats

<div align="center">
  <p>
    <img src="https://img.shields.io/badge/Public_Repos-15+-181717?style=for-the-badge&logo=github&logoColor=white" alt="Public Repos"/>
    <img src="https://img.shields.io/badge/Primary_Language-Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" alt="Primary Language"/>
    <img src="https://img.shields.io/badge/Focus-Flutter_&_Web3-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Focus"/>
  </p>
  <p>
    <img src="https://img.shields.io/badge/Commits-Active-success?style=flat-square&labelColor=2B2B2B" alt="Commits"/>
    <img src="https://img.shields.io/badge/Open_Source-Contributor-blue?style=flat-square&labelColor=2B2B2B" alt="Open Source"/>
    <img src="https://img.shields.io/badge/Code_Quality-Clean_Architecture-6DB33F?style=flat-square&labelColor=2B2B2B" alt="Code Quality"/>
  </p>
</div>

---

## 저장소 목록 | Repository Categories

<details>
<summary><b>포트폴리오 프로젝트 | Portfolio Projects</b></summary>

| 저장소 | 설명 | 기술 |
|--------|------|------|
| [Crypto-Wallet-Pro](https://github.com/kaywalker91/Crypto-Wallet-Pro) | 멀티체인 지갑 (Clean Architecture) | Flutter, Riverpod |
| [MindLog](https://github.com/kaywalker91/MindLog) | AI 감정 분석 다이어리 | Flutter, Groq API |
| [TimeWalker](https://github.com/kaywalker91/TimeWalker) | 인터랙티브 역사 교육 게임 | Flutter, Flame |
| [wallet_integration_practice](https://github.com/kaywalker91/wallet_integration_practice) | 멀티체인 지갑 연동 연습 | Flutter |

</details>

<details>
<summary><b>학습 & 실험 | Learning & Experiments</b></summary>

| 저장소 | 설명 | 기술 |
|--------|------|------|
| [Native-Lab](https://github.com/kaywalker91/Native-Lab) | Flutter Platform Channels 학습 | Flutter |
| [Flutter_Practice](https://github.com/kaywalker91/Flutter_Practice) | 반응형 UI + i18n (EN/KO/JA) | Flutter, Riverpod |

</details>

---

## 학력 & 자격증 | Education & Certifications

| 구분 | 내용 | 기간 |
|:----:|------|:----:|
| 학력 | 공주교육대학교 초등교육학과 학사 | 2012 - 2019 |
| 수료 | 클로드 코드 완벽 마스터 (Inflearn) | 2025 |
| 수료 | Flutter 실전 프로젝트 - BLoC & Riverpod (FastCampus) | 2025 |
| 수료 | Flutter & Dart Complete Guide (Udemy) | 2024 - 2025 |
| 자격증 | 한국사능력검정시험 1급 | 2021 |
| 자격증 | 정보처리기능사 | 2006 |

---

## 연락처 | Contact

> 함께 일하고 싶으시다면 연락주세요! 😊

<div align="center">
  <a href="mailto:eorkr112@naver.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://kaywalker.tistory.com">
    <img src="https://img.shields.io/badge/Blog-FF5722?style=for-the-badge&logo=blogger&logoColor=white" alt="Blog"/>
  </a>
  <a href="https://github.com/kaywalker91">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://kaywalker91.github.io/">
    <img src="https://img.shields.io/badge/Portfolio-02569B?style=for-the-badge&logo=github-pages&logoColor=white" alt="Portfolio"/>
  </a>
</div>

---

<div align="center">
  <sub>모바일 개발과 블록체인 기술에 대한 열정으로 만들었습니다</sub>
  <br/>
  <sub>Built with passion for mobile development and blockchain technology</sub>
</div>
