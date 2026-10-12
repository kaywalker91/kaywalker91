<div align="center">

# 김대각 / Kay

[English](README.md) | **한국어**

<p><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=02569B&center=true&vCenter=true&width=650&lines=Mobile+%26+Web+Development;Service+Reliability+Improvements;Tools+for+Everyday+Work" alt="모바일·웹 개발, 서비스 안정성 개선, 업무 도구" width="650" /></p>

</div>

**모바일·웹 개발, 안정성 개선, 업무 도구 기획·설계.**

인쇄 이미지 생성이 멈추거나 요소가 빠지는 문제를 개선하고, 외부 지갑 연결을 구현했습니다. 날짜·기념일 인쇄 오류를 찾는 검수 도구도 기획·설계하며, 사용자가 작업을 끝내는 데 필요한 흐름을 다뤄 왔습니다.

---

## 주요 경험

### PLLI LAB · 인쇄 이미지 생성 복구

**로운컴퍼니 · 2026.03–현재**

여러 주문의 인쇄 이미지를 만드는 중 브라우저 작업이 멈추거나 사진·스티커·텍스트가 빠지는 문제를 인계받아, 개선과 주문별 복구를 주도했습니다.

- **중단 뒤 이어가기:** 처리 진행을 보관하고 다음 세션에서 재개하도록 보강했습니다. 여러 탭이 같은 주문을 중복 처리하는 경로도 다뤘습니다.
- **누락 요소 복원:** 이미지 처리와 참조를 보완하고, 전후 인쇄 이미지를 눈으로 비교하며 복구를 확인했습니다.
- **성과:** 문제 주문의 처리를 재개하고 누락된 요소를 복원했습니다.

기술: 브라우저에서 인쇄 이미지를 만드는 `Flutter Web` · 화면을 이미지로 그리는 `CanvasKit / WebGL` · 주문·파일을 보관하는 `Firebase`

### 캘린더 QA · 인쇄 오류를 찾는 검수 도구

**로운컴퍼니 · 초기 기획·설계 담당**

달력·다이어리의 잘못된 날짜와 기념일 위치를 인쇄 전에 찾고, 디자이너가 검토할 위치를 쉽게 확인할 수 있는 도구를 기획·설계했습니다.

- **검사 상태 구분:** 내용을 읽지 못한 경우와 검사 결과 오류가 없는 경우를 구분하는 흐름을 설계했습니다.
- **위치를 찾는 보고:** 쪽수·칸 이름·인쇄 문구와 예상값을 함께 보여 주는 보고 방식을 마련했습니다.
- **성과:** 날짜 오식과 기념일 위치 오류를 탐지하고, 검사 범위를 넓혔습니다.

기술: PDF의 글자·위치를 읽고 규칙과 비교하는 `TypeScript` 기반 도구

### 포롱 · 외부 지갑 연결 흐름 구현

**FORLONG · 2025.12–2026.02**

서비스 앱과 지갑 앱을 오가며 승인·서명하는 동안 복귀 시점과 응답 순서가 엇갈리는 문제를 다뤘습니다. 계획서로 인계받은 지갑 연결의 구현을 담당했습니다.

- **단계별 처리:** 연결 대기·서명·검증을 나누고, 앱으로 돌아온 링크를 처리할 시점까지 보관하도록 구현했습니다.
- **응답 충돌 대응:** 중복 재연결을 제한하고, 새 서명·주소를 늦게 도착한 조회 결과가 덮지 않도록 보완했습니다.
- **성과:** 연결 단계·링크 처리·지갑별 오류 대응 코드와 시험 정의를 작성했습니다.

기술: 앱 개발 `Flutter / Dart` · 외부 지갑 연결 `WalletConnect v2` · 진행 단계에 따라 다음 동작을 결정하는 `State Machine`

---

## 모바일 서비스 개발 경험

### 플레이스링크 · 포인트투어의 작업 처리 개선

**PlaceLink · 2022.10–2024.11**

포인트투어는 장소 방문과 매장 이용을 포인트·혜택에 연결하는 앱입니다. 서버 응답을 기다리는 작업에서 오류 대응이 복잡해지는 문제를 다루며 Android 앱의 처리 구조를 개선했습니다.

- **담당한 일:** AsyncTask 기반 비동기 처리를 RxJava 2로 전환하고, 요청·응답·오류 처리 흐름을 정리했습니다.
- **해결 과정:** 서버 요청과 응답 해석을 화면 표시에서 분리하고, 결과가 도착하면 화면을 갱신하도록 연결했습니다.
- **성과:** FAQ·축제 매장 상세 화면을 RxJava 2 기반으로 전환했습니다. 앱 구조·축제 운영·업데이트·정기 점검 절차를 인수인계 문서로 정리했습니다.

기술: Android 앱 개발 `Java` · 서버 응답·오류 흐름 연결 `RxJava 2`

### 시선아이티 · 재난안전 앱의 Flutter 전환

**Seesun IT · 2024.11–2025.11**

안전디딤돌·이머전시레디의 Android·iOS 앱을 공통 코드로 옮기며, 위치·날씨·재난 정보를 갱신하고 화면에 반영하는 문제를 다뤘습니다.

- **담당한 일:** Android·iOS 앱의 Flutter 전환과 데이터 상태 관리를 담당했습니다.
- **해결 과정:** 데이터가 바뀌면 관련 화면이 받아 표시하도록 Riverpod으로 상태를 연결하고, 조회·저장을 공통 창구에서 처리하는 구조로 정리했습니다.
- **성과:** 위치 조회와 저장 상태를 분리하고, 위치·권한·날씨 변화에 따라 날씨 화면이 갱신되도록 구현했습니다.

기술: 공통 앱 개발 `Flutter / Dart` · 데이터 변화와 화면 연결 `Riverpod`

---

## 직접 개발하고 사용하는 앱

### LinkNote · 링크 저장·분류

**개발 중 · 내부테스트에서 직접 사용**

YouTube 공유 후 저장 화면이 열리지 않는 문제를 고치고, 분류 선택 창이 조회 중·실패·빈 목록을 구분하도록 개선했습니다. 링크를 저장할 때 분류도 함께 고를 수 있게 연결했습니다. 분석부터 구현, 실기기 확인까지 직접 했습니다.

2026.10.08 기준 내부테스트 앱을 직접 사용하고 있으며, 분류 선택 창의 정상 동작을 확인했습니다.

[GitHub 저장소](https://github.com/kaywalker91/LinkNote)

### MindLog · AI 일기 분석

**Google Play 출시 · 개발·유지보수 중**

AI로 일기를 분석하는 앱을 직접 기획·설계·구현하고 사용하고 있습니다. 개발 버전에서는 작성 중인 글·날짜·사진을 초안으로 보관하고, 화면 이탈 때 저장하며 다시 불러오는 임시저장 기능을 구현했습니다.

[Google Play](https://play.google.com/store/apps/details?id=com.mindlog.mindlog) · [GitHub 저장소](https://github.com/kaywalker91/MindLog) · [웹 데모](https://kaywalker91.github.io/MindLog/)

그 밖의 프로젝트: [TimeWalker](https://kaywalker91.github.io/TimeWalker/)

---

## 기술 스택

<div align="center">

<img src="https://skillicons.dev/icons?i=flutter,dart,java,ts,firebase,git&theme=dark&perline=6" alt="Flutter, Dart, Java, TypeScript, Firebase, Git" />

</div>

- **앱·웹:** `Flutter / Dart`, `Flutter Web`, `Android / Java`로 화면과 서비스 흐름을 구현합니다.
- **데이터·연동:** `Riverpod`으로 데이터 변화와 화면을 연결하고, `Firebase`로 주문·파일을 보관하며, `WalletConnect`로 외부 지갑을 연동합니다.
- **AI 도구:** `Claude Code`로 분석·구현을 진행하고, `Codex` 등 다른 모델의 리뷰를 거친 뒤 결과를 직접 검증해 반영합니다.

---

<div align="center">

[![이메일](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:eorkr112@naver.com)
[![블로그](https://img.shields.io/badge/Blog-EB5B00?style=for-the-badge&logo=tistory&logoColor=white)](https://kaywalker.tistory.com)
[![포트폴리오](https://img.shields.io/badge/Portfolio-181717?style=for-the-badge&logo=github&logoColor=white)](https://kaywalker91.github.io/)

</div>
