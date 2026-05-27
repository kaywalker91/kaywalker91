<div align="center">

# Daegak Kim

**English** | [한국어](README.ko.md)

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=02569B&center=true&vCenter=true&width=650&lines=Flutter+Performance+%26+Reliability+Engineer;CanvasKit+%C2%B7+OOM+%C2%B7+Crash-free+at+Scale;AI-Orchestrated+Development" alt="Typing SVG" /></a>

<img src="https://komarev.com/ghpvc/?username=kaywalker91&style=flat-square&color=02569B" alt="Profile Views"/>

</div>

**Flutter engineer specializing in performance, reliability, and full-cycle delivery across mobile & web.**

Beyond building UI, I dig into rendering pipelines, memory, and crashes to fix root-cause bottlenecks in production — 4 years in.

---

## Featured Work

### PLLI Lab — Flutter Web Mass-Rendering Pipeline
**Mass print-image rendering pipeline** · Rowoon Company Corp. (2026.03 ~ Present)

Designed a CanvasKit-based pipeline that renders print images at scale on Flutter Web (160 commits / 25 days).

- **Browser runtime stability**: JS+WASM memory monitoring, OOM session splitting, WebGL stability engineering
- **Flow control**: 100-item chunked batching with `Completer`-based pause/resume (eliminated busy-wait)
- **Resilience**: 3-stage sticker fallback chain · CanvasKit decoding-limit workaround (HTML Canvas downsampling)
- **Ops & observability**: daily 21:00 auto-render schedule, Web Lock distributed locking, Crashlytics diagnostics

Tech: `Flutter Web` `CanvasKit/WebGL` `Web Lock API` `Performance Memory API` `Firebase`

### Multi-chain Crypto Wallet & Social Trading
**Multi-chain crypto wallet / social trading** · FORLONG (2025.12 ~ 2026.03)

Stabilized a complex wallet-connection flow with a state-machine architecture.

- 4-layer adapter architecture integrating **WalletConnect v2**
- 4-layer **Sign Guard** to defend against race conditions
- Context-based deep-link routing with cold-start session recovery
- **Result: ~90% reduction in wallet-connection failures** · 15-module Clean Architecture

Tech: `Flutter` `Riverpod 3.x` `WalletConnect v2` `Clean Architecture` `State Machine`

### Disaster-Safety Apps — Korea's official services
**National disaster-safety service** · SISUN IT (2024.11 ~ 2025.11)

Solo-led the legacy → Flutter migration of two separate apps: **Safety Dideumdol (안전디딤돌)** for Korean residents and **Emergency Ready App** for foreign visitors.

- **30% fewer bugs, 20% faster development** after introducing a Riverpod architecture
- **95% accessibility compliance** (TalkBack / VoiceOver)
- Location-based FCM auto-subscribe (GPS) · 19-language real-time translation (Google Translate API V3)

### PointTour — Location-based rewards app
**Location-based point rewards** · PlaceLink (2022.10 ~ 2024.11)

- Refactored AsyncTask → **RxJava2**, eliminating async crashes by **80–90%**
- **400% download growth** (1,000 → 5,000) driven by the Daejeon "0-si Festival" event integration

---

## AI-Orchestrated Workflow

I leverage AI coding agents (**Claude Code**, **Antigravity**) across my workflow — spec breakdown, implementation acceleration, debugging hypotheses, test scaffolding, and review loops — to cut iteration time on complex migrations and refactors.

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

- **MindLog** — AI emotional-journaling app (Llama 3.3 analysis + 2-layer safety filter). [Google Play](https://play.google.com/store/apps/details?id=com.mindlog.mindlog) · [Live Demo](https://kaywalker91.github.io/MindLog/)
- **TimeWalker** — History-education game built on the Flame engine (branching dialogue + offline-first). [Live Demo](https://kaywalker91.github.io/TimeWalker/)

---

<div align="center">

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:eorkr112@naver.com)
[![Blog](https://img.shields.io/badge/Blog-EB5B00?style=for-the-badge&logo=tistory&logoColor=white)](https://kaywalker.tistory.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-181717?style=for-the-badge&logo=github&logoColor=white)](https://kaywalker91.github.io/)

</div>
