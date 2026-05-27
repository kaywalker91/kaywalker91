<div align="center">

# 김대각

[English](README.md) | **한국어**

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=02569B&center=true&vCenter=true&width=650&lines=Flutter+Performance+%26+Reliability+Engineer;CanvasKit+%C2%B7+OOM+%C2%B7+Crash-free+at+Scale;AI-Orchestrated+Development" alt="Typing SVG" /></a>

<img src="https://komarev.com/ghpvc/?username=kaywalker91&style=flat-square&color=02569B" alt="Profile Views"/>

</div>

**성능·안정성과 풀사이클 설계에 강점을 둔 모바일·웹 크로스플랫폼 Flutter 엔지니어.**

단순 화면 구현을 넘어 렌더링 파이프라인·메모리·크래시 같은 근본 병목을 끝까지 파고들어 실서비스 문제를 해결하는 4년차 엔지니어입니다.

---

## 주요 프로젝트

### PLLI Lab — Flutter Web 대량 렌더링 파이프라인
**대량 인쇄 이미지 렌더링 파이프라인** · 로운컴퍼니씨앤씨 (2026.03 ~ 재직 중)

Flutter Web에서 인쇄 이미지를 대량으로 렌더링하는 CanvasKit 기반 파이프라인을 설계했습니다 (160커밋 / 25일).

- **브라우저 런타임 안정성**: JS+WASM 메모리 모니터링, OOM 세션 분할, WebGL 안정성 엔지니어링
- **흐름 제어**: 100건 청크 배치 + `Completer` 기반 pause/resume (busy-wait 제거)
- **복원력**: 3단계 스티커 폴백 체인 · CanvasKit 디코딩 한계 우회 (HTML Canvas 다운샘플링)
- **운영·관측성**: 매일 21시 자동 렌더링 스케줄, Web Lock 분산 락, Crashlytics 진단

기술: `Flutter Web` `CanvasKit/WebGL` `Web Lock API` `Performance Memory API` `Firebase`

### 멀티체인 크립토 지갑 & 소셜 트레이딩
**멀티체인 크립토 지갑 / 소셜 트레이딩** · FORLONG (2025.12 ~ 2026.03)

State Machine 아키텍처로 복잡한 지갑 연결 흐름을 안정화했습니다.

- **WalletConnect v2** 를 통합한 4계층 어댑터 아키텍처
- Race Condition 방어를 위한 4계층 **Sign Guard**
- Cold Start 세션 복구를 포함한 Context 기반 딥링크 라우팅
- **성과: 지갑 연결 실패율 약 90% 감소** · 15개 모듈 Clean Architecture

기술: `Flutter` `Riverpod 3.x` `WalletConnect v2` `Clean Architecture` `State Machine`

### 재난안전 서비스 — 행정안전부 공식 앱
**국가 재난안전 서비스** · 시선아이티 (2024.11 ~ 2025.11)

두 개의 별도 앱 — 내국인용 **안전디딤돌** 과 외국인용 **Emergency Ready App** — 의 레거시 → Flutter 전환을 단독 수행했습니다.

- Riverpod 아키텍처 도입으로 **버그 30%↓, 개발 속도 20%↑**
- **접근성 준수율 95%** (TalkBack / VoiceOver)
- GPS 기반 위치 FCM 자동 구독 · Google Translate API V3로 19개 언어 실시간 번역

### 포인트투어 — 위치 기반 포인트 적립 앱
**위치 기반 포인트 적립** · 플레이스링크 (2022.10 ~ 2024.11)

- AsyncTask → **RxJava2** 리팩토링으로 비동기 크래시 **80~90% 감소**
- 대전 "0시 축제" 이벤트 연계로 **다운로드 400% 성장** (1,000 → 5,000)

---

## AI 오케스트레이션 워크플로우

AI 코딩 에이전트(**Claude Code**, **Antigravity**)를 스펙 분해·구현 가속·디버깅 가설 검증·테스트 스캐폴딩·리뷰 루프 전반에 활용하여, 복잡한 마이그레이션과 리팩토링의 반복 작업 리드타임을 단축합니다.

---

## 기술 스택

<div align="center">
<img src="https://skillicons.dev/icons?i=flutter,dart,firebase,java,swift,js,postgres,git&theme=dark&perline=8" alt="Tech Stack" />
</div>

**모바일 / 웹**: Flutter, Dart, Flutter Web, Android (Java), iOS (Swift)
**아키텍처**: Clean Architecture, MVVM, Riverpod, State Machine
**성능 / 안정성**: CanvasKit/WebGL, OOM 대응, Crashlytics, Web Lock API
**Web3**: WalletConnect v2, EVM 멀티체인 (Ethereum, BNB Chain, Base)

---

## 사이드 프로젝트

- **MindLog** — AI 감정일기 앱 (Llama 3.3 분석 + 2단계 안전 필터). [Google Play](https://play.google.com/store/apps/details?id=com.mindlog.mindlog) · [Live Demo](https://kaywalker91.github.io/MindLog/)
- **TimeWalker** — Flame 엔진 기반 역사 교육 게임 (분기형 대화 + 오프라인 우선). [Live Demo](https://kaywalker91.github.io/TimeWalker/)

---

<div align="center">

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:eorkr112@naver.com)
[![Blog](https://img.shields.io/badge/Blog-EB5B00?style=for-the-badge&logo=tistory&logoColor=white)](https://kaywalker.tistory.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-181717?style=for-the-badge&logo=github&logoColor=white)](https://kaywalker91.github.io/)

</div>
