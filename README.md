<div align="center">

# Daegak Kim / Kay

**English** | [한국어](README.ko.md)

<p><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=02569B&center=true&vCenter=true&width=650&lines=Mobile+%26+Web+Development;Service+Reliability+Improvements;Tools+for+Everyday+Work" alt="Mobile and web development, service reliability improvements, and tools for everyday work" width="650" /></p>

</div>

**Mobile and web development, reliability improvements, and tools for everyday work.**

I improve interrupted or incomplete print-image generation and implement external wallet connections. I also planned and designed tools for detecting printed date and holiday errors, focusing on the steps people need to complete their work.

---

## Selected work

### PLLI LAB · Recovering print-image generation

**Rowoon Company · Mar 2026–Present**

I took over interrupted browser processing and missing photo, sticker, and text issues in print-image generation, and led improvements and recovery for affected orders.

- **Resuming interrupted work:** Improved progress storage and recovery in a later session, and addressed duplicate processing of the same order across browser tabs.
- **Restoring missing elements:** Improved image processing and references, and compared output images visually to check recovery.
- **Confirmed changes:** Historical processing records and before-and-after outputs show resumed processing and restored elements for specific orders. The results cover those orders and elements.

Tech: `Flutter Web` for browser-based print-image generation · `CanvasKit / WebGL` for drawing images · `Firebase` for storing orders and files

### Calendar QA · Tools for finding print errors

**Rowoon Company · Initial planning and design**

I planned and designed a tool to detect incorrect dates and holiday positions in calendars and diaries before printing, and help designers locate the content to review.

- **Distinguishing inspection states:** Designed a flow that separates unreadable content from an inspection with no errors.
- **Locating issues:** Defined a reporting approach that shows the page, cell name, printed text, and expected value together.
- **Tool results:** Archived inspection records show date and holiday-position error detection and improved inspection coverage. My responsibilities were initial planning and design; the tool detects and reports errors.

Tech: A `TypeScript` tool that reads PDF text and positions and compares them with rules

### FORLONG · Implementing external wallet connections

**FORLONG · Dec 2025–Feb 2026**

I addressed return timing and out-of-order responses as users moved between the service and wallet apps for approval and signing. I was responsible for implementing the wallet connection work handed over through a plan.

- **Step-by-step handling:** Implemented separate connection, signing, and verification stages, retaining return links until they could be processed.
- **Response conflicts:** Limited overlapping reconnections and prevented delayed queries from overwriting newer signatures and addresses.
- **Implementation results:** Produced connection-state, link-handling, and wallet-specific error-handling code and test definitions. These are distinct from complete real-wallet flow validation or a production launch.

Tech: `Flutter / Dart` for app development · `WalletConnect v2` for wallet integration · `State Machine` for choosing the next action based on the current stage

---

## Mobile service development

### PlaceLink · Improving task handling in PointTour

**PlaceLink · Oct 2022–Nov 2024**

PointTour connects place visits and store use with points and benefits. I worked on the Android processing structure as tasks waiting for server responses made error handling harder to manage.

- **My role:** My existing résumé records migrating AsyncTask-based work to RxJava 2 and organizing the request, response, and error flow.
- **Approach:** Separated server requests and response parsing from screen updates, then connected incoming results to the UI. RxJava connects asynchronous work with its results and error handling.
- **Confirmed changes and artifacts:** Historical code comparisons confirm selected migrations in FAQ and festival-store details. Handover documents under my name also describe app structure, festival operations, updates, and regular checks.

Tech: `Java` for Android development · `RxJava 2` for server-response and error handling

### Seesun IT · Flutter migration for disaster-safety apps

**Seesun IT · Nov 2024–Nov 2025**

While moving the Android and iOS versions of Safety Dideumdol and Emergency Ready to shared code, I worked on updating location, weather, and disaster information and reflecting it in the right screens.

- **My role:** My existing résumé records responsibility for Flutter migration and data-state management. Flutter allows Android and iOS screens to share application code.
- **Approach:** Connected data changes to screens through Riverpod and organized data reads and writes through a common access layer.
- **Confirmed implementation:** Code from my employment period separates location retrieval and stored state, and updates the weather screen in response to location, permission, and weather-state changes. My responsibilities are supported by résumé records; implementation changes by historical code comparisons.

Tech: `Flutter / Dart` for shared app development · `Riverpod` for connecting data changes to screens

---

## Apps I develop and use

### LinkNote · Saving and organizing links

**In development · Personally used in internal testing**

I fixed a flow where sharing from YouTube did not open the save screen, and improved the collection picker to distinguish loading, failure, and an empty list. I also connected collection selection to the link-saving form. I handled analysis, implementation, and device checks for these two cases.

As of Oct 8, 2026, I personally use the internal-test app and have confirmed that the collection picker works.

[GitHub repository](https://github.com/kaywalker91/LinkNote)

### MindLog · AI diary analysis

**Released on Google Play · In active development and maintenance**

I planned, designed, implemented, and personally use this AI diary-analysis app. In later development, I implemented draft storage and restoration for text, dates, and photos, including saving when leaving the writing screen.

Release, maintenance, and personal use are current as of Oct 8, 2026. Draft improvements refer to development code, separately from feature-by-feature testing of the current public build.

[Google Play](https://play.google.com/store/apps/details?id=com.mindlog.mindlog) · [GitHub repository](https://github.com/kaywalker91/MindLog) · [Web demo](https://kaywalker91.github.io/MindLog/)

Other work: [TimeWalker](https://kaywalker91.github.io/TimeWalker/)

---

## Tech and AI collaboration

<div align="center">

<img src="https://skillicons.dev/icons?i=flutter,dart,java,ts,firebase,git&theme=dark&perline=6" alt="Flutter, Dart, Java, TypeScript, Firebase, Git" />

</div>

- **Apps and web:** I use `Flutter / Dart`, `Flutter Web`, and `Android / Java` to implement screens and service flows.
- **Data and integrations:** I use `Riverpod` to connect data changes to screens, `Firebase` to store orders and files, and `WalletConnect` to integrate external wallets.

I used AI tools while resolving PLLI LAB issues. Relevant wallet-connection code at FORLONG and related LinkNote and MindLog code include Claude co-author records. I describe both my responsibilities and AI co-authorship.

---

<div align="center">

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:eorkr112@naver.com)
[![Blog](https://img.shields.io/badge/Blog-EB5B00?style=for-the-badge&logo=tistory&logoColor=white)](https://kaywalker.tistory.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-181717?style=for-the-badge&logo=github&logoColor=white)](https://kaywalker91.github.io/)

</div>
