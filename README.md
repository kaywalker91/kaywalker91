<div align="center">

# Daegak Kim

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=02569B&center=true&vCenter=true&width=540&lines=Flutter+Performance+%26+Reliability+Engineer;CanvasKit+%C2%B7+OOM+%C2%B7+Crash-free+at+Scale;AI-Orchestrated+Development" alt="Typing SVG" /></a>

<img src="https://komarev.com/ghpvc/?username=kaywalker91&style=flat-square&color=02569B" alt="Profile Views"/>

</div>

**Flutter engineer specializing in performance, reliability, and full-cycle delivery across mobile & web.**

모바일·웹 크로스플랫폼에서 실서비스 성능 병목과 안정성 문제를 구조적으로 해결합니다. 단순 화면 구현을 넘어, 렌더링 파이프라인·메모리·크래시 같은 근본 병목을 끝까지 파고드는 4년차 엔지니어입니다.

---

## Featured Work

### PLLI Lab — Flutter Web Mass-Rendering Pipeline
**대량 인쇄 이미지 렌더링 파이프라인** · 로운컴퍼니씨앤씨 (2026.03 ~ Present)

Designed a CanvasKit-based pipeline that renders print images at scale on Flutter Web (160 commits / 25 days).

- **Browser runtime stability**: JS+WASM memory monitoring, OOM session splitting, WebGL stability engineering
- **Flow control**: 100-item chunked batching with `Completer`-based pause/resume (eliminated busy-wait)
- **Resilience**: 3-stage sticker fallback chain · CanvasKit decoding-limit workaround (HTML Canvas downsampling)
- **Ops & observability**: daily 21:00 auto-render schedule, Web Lock distributed locking, Crashlytics diagnostics

Tech: `Flutter Web` `CanvasKit/WebGL` `Web Lock API` `Performance Memory API` `Firebase`

### iLity Hub — Multi-chain Crypto Wallet & Social Trading
**멀티체인 크립토 지갑 / 소셜 트레이딩** · FORLONG (2025.12 ~ 2026.03)

Stabilized a complex wallet-connection flow with a state-machine architecture.

- 4-layer adapter architecture integrating **WalletConnect v2**
- 4-layer **Sign Guard** to defend against race conditions
- Context-based deep-link routing with cold-start session recovery
- **Result: ~90% reduction in wallet-connection failures** · 15-module Clean Architecture

Tech: `Flutter` `Riverpod 3.x` `WalletConnect v2` `Clean Architecture` `State Machine`

### Emergency Ready App (안전디딤돌) — Korea's official disaster-safety app
**행정안전부 재난안전 서비스** · 시선아이티 (2024.11 ~ 2025.11)

Solo-led the migration of legacy Android (Java) + iOS to Flutter.

- **30% fewer bugs, 20% faster development** after introducing a Riverpod architecture
- **95% accessibility compliance** (TalkBack / VoiceOver)
- Location-based FCM auto-subscribe (GPS) · 19-language real-time translation (Google Translate API V3)

### PointTour (포인트투어) — Location-based rewards app
**위치 기반 포인트 적립** · 플레이스링크 (2022.10 ~ 2024.11)

- Refactored AsyncTask → **RxJava2**, eliminating async crashes by **80–90%**
- **400% download growth** (1,000 → 5,000) driven by the Daejeon "0-si Festival" event integration

---

## AI-Orchestrated Workflow

I leverage AI coding agents (**Claude Code**, **Antigravity**) across my workflow — spec breakdown, implementation acceleration, debugging hypotheses, test scaffolding, and review loops — to cut iteration time on complex migrations and refactors.

> 레거시 마이그레이션·리팩토링·테스트 작성 구간에서 AI 에이전트를 파이프라인화하여 반복 작업 리드타임을 단축합니다.

---

## Tech

<div align="center">
<img src="https://skillicons.dev/icons?i=flutter,dart,firebase,java,swift,js,postgres,git&theme=dark&perline=8" alt="Tech Stack" />
</div>

**Mobile / Web**: Flutter, Dart, Flutter Web, Android (Java), iOS (Swift)
**Architecture**: Clean Architecture, MVVM, Riverpod, State Machine
**Performance / Reliability**: CanvasKit/WebGL, OOM mitigation, Crashlytics, Web Lock API
**Web3**: WalletConnect v2, EVM multi-chain (Ethereum, BNB Chain, Base)

---

## Side Projects

- **MindLog** — AI 감정일기 (Llama 3.3 기반 분석 + 2단계 안전 필터). [Google Play](https://play.google.com/store/apps/details?id=com.mindlog.mindlog) · [Live Demo](https://kaywalker91.github.io/MindLog/)
- **TimeWalker** — Flame 엔진 기반 역사 교육 게임 (분기형 대화 + 오프라인 우선). [Live Demo](https://kaywalker91.github.io/TimeWalker/)

---

<div align="center">

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:eorkr112@naver.com)
[![Blog](https://img.shields.io/badge/Blog-EB5B00?style=for-the-badge&logo=tistory&logoColor=white)](https://kaywalker.tistory.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-181717?style=for-the-badge&logo=github&logoColor=white)](https://kaywalker91.github.io/)

</div>
