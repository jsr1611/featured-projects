# Featured Projects — Jumanazar Saidov

Backend engineer (Java · Spring Boot · Microservices), Seoul, South Korea.
6+ years building microservices, REST APIs and data pipelines across
automotive, government and SaaS platforms.

Three lists below: **featured projects** (professional and research work),
**my own products** (apps I build and ship, with downloads), and **other
personal projects**. Client and employer source code is private — those links
point to the live product.

**CV** — [JumanazarSaidov_CV_2026.pdf](JumanazarSaidov_CV_2026.pdf)

**Contact** — [GitHub @jsr1611](https://github.com/jsr1611) ·
[LinkedIn](https://linkedin.com/in/jsr1611) ·
[Telegram @jsr1611](https://t.me/jsr1611) ·
jumanazar.saidov@gmail.com

# Featured projects

Professional and research work — the systems I built for employers and clients,
plus the tools that came out of them.

| Project | Client / context | Period | Stack |
|---|---|---|---|
| [AI automation for enterprise ERP](#ai-erp) | PromDav AI Solutions – David E&C | 2026-06 → present | Java, Spring Boot, LLM integration |
| [TheHelloApp](#thehelloapp) | Toptal (contract) | 2025-02 → 2025-12 | Java, Spring Boot, SQL, microservices |
| [MSIS Cloud Solution](#msiscloud) | MSIS Lab | 2024-09 → 2026-04 | Next.js, React, Django REST, PostgreSQL |
| [Hyundai connected car data integration](#hyundai) | FPT Software Korea → Hyundai AutoEver America | 2024-05 → 2025-03 | Java 17/21, Spring Boot, Kafka, Kubernetes |
| [BUBE Portal](#bube) | AttoLabs EU | 2023-08 → 2024-04 | Kotlin, Spring Boot, Angular |
| [Seoul Danurim](#danurim) | SweetK Co., Ltd. | 2022 – 2023 | Java, Spring Boot, CMS |
| [VisitSeoul CMS](#visitseoul) | SweetK Co., Ltd. | 2022 | Java, Spring Boot |
| [pdf2json](#pdf2json) | Research tooling | 2022 | Python, FastAPI |
| [Intelligent Monitoring Solution](#monitoring) | DLIT Co., Ltd. | 2021 | C#, MS SQL, IoT |
| [Efficient object labeling tool](#labeling-tool) | MSIS Lab, Chungbuk Nat'l Univ. | 2020 – 2022 | Python, OpenCV, YOLOv3 |

---

<a id="ai-erp"></a>
## AI automation for enterprise ERP — [David E&C](http://www.davidenc.com)

Lead engineer for AI-driven automation of enterprise ERP workflows and email
processing pipelines at PromDav AI Solutions. Designing scalable backend
architectures that integrate LLM capabilities into legacy enterprise systems,
and setting the technical strategy, system designs (TDDs) and engineering
standards across the AI integration pipeline.

- **Period** — 2026-06 → present · **Role** — Lead Software Engineer
- **Stack** — Java, Spring Boot, microservices, LLM integration
- **Link** — [davidenc.com](http://www.davidenc.com)

---

<a id="thehelloapp"></a>
## TheHelloApp — [thehelloapp.com](https://thehelloapp.com)

Senior backend engineer on a live SaaS product via Toptal. Cut history-log API
response time **10×** by profiling slow SQL, adding composite indices and
removing N+1 queries across three microservices. Redesigned the legacy chat
service into a single-thread architecture that enabled per-user read statuses
and reduced support tickets by 30%. Authored the technical design documents for
4+ core features and ran 50+ code reviews that established performance
guidelines and cut production hotfixes.

- **Period** — 2025-02 → 2025-12 · **Role** — Senior Software Engineer (contract)
- **Stack** — Java, Spring Boot, SQL tuning, microservices
- **Link** — [thehelloapp.com](https://thehelloapp.com)

---

<a id="msiscloud"></a>
## MSIS Cloud Solution

Cloud platform for [MSIS Lab](https://www.msislab.com/): a Next.js/React
frontend over a Django REST Framework backend on PostgreSQL, with documented
Open API endpoints and a versioned database schema.

- **Period** — 2024-09 → 2026-04
- **Stack** — Next.js, React, JavaScript, SCSS · Django REST Framework, PostgreSQL
- **Link** — source: private (`msiscloud_solution`)

---

<a id="hyundai"></a>
## Connected car data integration — [Hyundai AutoEver America](https://haeaus.com/)

Backend work on Hyundai's Connected Car Data Integration platform, delivered
through [FPT Software Korea](https://fptsoftware.kr/). Designed RESTful APIs in
Java 17/21, Spring Boot and Kafka while migrating 5+ legacy modules into
microservices. Built ETL pipelines in Java and Node.js that moved and
transformed **2M+ records** across PostgreSQL, MongoDB and Oracle with zero data
loss. Maintained Kubernetes CI/CD pipelines (ArgoCD), cutting deployment time
25% through parallelized builds and caching, and developed internal admin UI
tools that reduced manual configuration effort by 40%.

- **Period** — 2024-05 → 2025-03 · **Role** — Senior Software Engineer (contract)
- **Stack** — Java 17/21, Spring Boot, Kafka, PostgreSQL, MongoDB, Oracle, Kubernetes, ArgoCD
- **Links** — [haeaus.com](https://haeaus.com/) · [fptsoftware.kr](https://fptsoftware.kr/)

---

<a id="bube"></a>
## BUBE Portal — [bube-portal.de](https://bube-portal.de)

German national environmental data reporting platform serving **16 federal
states**, built at [AttoLabs EU](https://attolabs.eu/). Developed RESTful APIs
in Kotlin/Spring Boot and Angular UI components, resolved 50+ bugs and
vulnerabilities, reviewed 3–5 PRs daily and held code coverage above 85% with
JUnit and Mockito.

- **Period** — 2023-08 → 2024-04 · **Role** — Software Engineer
- **Stack** — Kotlin, Spring Boot, Angular, JUnit, Mockito
- **Link** — [bube-portal.de](https://bube-portal.de)

---

<a id="danurim"></a>
## Seoul Danurim — [seouldanurim.net](https://seouldanurim.net)

Seoul's barrier-free tourism portal — accessible travel information for
visitors with disabilities, older travellers and families. Backend and CMS work
at SweetK Co., Ltd. alongside VisitSeoul.

- **Period** — 2022 – 2023 · **Role** — Software Engineer
- **Stack** — Java, Spring Boot, CMS
- **Link** — [seouldanurim.net](https://seouldanurim.net)

---

<a id="visitseoul"></a>
## VisitSeoul CMS — [visitseoul.net](https://VisitSeoul.net)

Content management backend for Seoul's official tourism portal, built at
[SweetK Co., Ltd.](https://www.sweetk.co.kr/) Backend APIs and admin features
for editors publishing multilingual tourism content.

- **Period** — 2022 · **Role** — Software Engineer
- **Stack** — Java, Spring Boot
- **Links** — live: [visitseoul.net](https://VisitSeoul.net) · source: private (`visit_seoul_cms`)

---

<a id="pdf2json"></a>
## pdf2json — journal paper extraction API

Converts PDF journal papers into structured text (JSON) for downstream
research tooling. Python extraction pipeline exposed as a FastAPI service with
generated Open API documentation.

- **Period** — 2022
- **Stack** — Python, FastAPI, Jupyter
- **Link** — source: private (`pdf2json`)

---

<a id="monitoring"></a>
## Intelligent Monitoring Solution

Data collection application bundle for IoT sensor devices — real-time
collection and visualization, deployed in semiconductor manufacturing clean
rooms at [DLIT Co., Ltd.](https://www.dlit.co.kr/)

- **Period** — 2021 · **Role** — Software Engineer
- **Stack** — C#, Java, MS SQL
- **Link** — [github.com/jsr1611/Intelligent_Monitoring_Solution](https://github.com/jsr1611/Intelligent_Monitoring_Solution)

---

<a id="labeling-tool"></a>
## Efficient object labeling tool

Image annotation and detection tool developed as a Graduate Research Assistant
at MSIS Lab, Chungbuk National University. Built on YOLOv3 with OpenCV;
model fine-tuning raised detection accuracy from **65% to 100%** on the target
dataset.

- **Period** — 2020 – 2022 · **Context** — [MSIS Lab](https://www.msislab.com/)
- **Stack** — Python, OpenCV, YOLOv3
- **Link** — [github.com/jsr1611/efficient_object_labeling_tool](https://github.com/jsr1611/efficient_object_labeling_tool)

---

# My own products

Applications I designed, built and ship myself. Installers are on the
[Releases](../../releases) page; they are not code-signed yet, so Windows
SmartScreen may warn on first run — choose **More info → Run anyway**.

| Product | Type | Built | Stack | Get it |
|---|---|---|---|---|
| [NurPhoto](#nurphoto) | Desktop app | 2026-07 | Tauri v2, Rust | [Download](../../releases/tag/nurphoto-v0.1.0) |
| [NurMail](#nurmail) | Android app | 2026-07 | Kotlin, Compose | [Download APK](../../releases/tag/nurmail-v1.0.0) |
| [NurMedia](#nurmedia) | Desktop app | 2026-07 | Tauri v2, Rust, ffmpeg | [Download](../../releases/tag/nurmedia-v0.1.0) |
| [Nurly](#nurly) | Android app | 2026-07 | Kotlin, Compose, Media3 | [Download APK](../../releases/tag/nurly-v0.1.14) |
| [Nur Player](#nur-player) | Android app | 2025-09 → 2026-07 | Java, AndroidX Media | [Download APK](../../releases/tag/nur-player-v1.0) |
| [HTTP Client](#http-client) | Desktop app | 2026-07 | Tauri v2, Rust | [Download](../../releases/tag/http-client-v0.1.0) |
| [YuklabBar bot](#yuklabbar) | Telegram bot | 2022 → present | Python, yt-dlp | [@yuklabbar_bot](https://t.me/yuklabbar_bot) |
| [Damir Yo'l Chiptachi bot](#chiptachi) | Telegram bot | 2026 | Node.js, Telegram Bot API | [@damiryolchiptachi_bot](https://t.me/damiryolchiptachi_bot) |
| [jumanazar.uz](#arabic-learning-platform) | Web platform | 2023-12 → present | Angular, Node.js, MongoDB | [jumanazar.uz](https://jumanazar.uz) |

---

<a id="nurphoto"></a>
## NurPhoto — desktop photo workbench

<img src="assets/nurphoto.png" alt="NurPhoto icon" width="96" align="right">

Everyday photo editing plus compliant **ID, passport and visa photos**. Open,
straighten, rotate, flip, crop with aspect presets, adjust tone, sharpen, and
export with real control over pixel size, DPI and file size.

Document presets lock the frame, configure the whole export (pixels, DPI, byte
ceiling, background), position the face automatically against the spec's
guides, and report compliance afterwards. Print sheets tile the photo at exact
physical size. Everything runs locally — identity documents never leave the
machine: no upload, no account, no server.

- **Built** — 2026-07
- **Platforms** — Windows, Linux, macOS
- **Stack** — Tauri v2, Rust, HTML/JS in the system WebView
- **Download** — [Windows installer (.exe)](../../releases/download/nurphoto-v0.1.0/NurPhoto_0.1.0_x64-setup.exe) ·
  [MSI](../../releases/download/nurphoto-v0.1.0/NurPhoto_0.1.0_x64_en-US.msi) — v0.1.0, ~6 MB
- **Source** — private

<!-- screenshots: drop files in screenshots/nurphoto/ and uncomment
<p>
  <img src="screenshots/nurphoto/editor.png" width="45%">
  <img src="screenshots/nurphoto/document-preset.png" width="45%">
</p>
-->

---

<a id="nurmail"></a>
## NurMail — local-first Android email client

Minimalist mail without the bloat. IMAP/POP3 receiving and optional SMTP
sending, with server settings auto-detected from the email domain.

The on-device database is the source of truth — the server mailbox is never
modified unless you opt in. A trainable naive-Bayes spam filter learns from
*Mark as spam* / *Not spam*; full-text search covers subject, sender, body and
attachment names; HTML mail renders in a WebView with remote images blocked by
default (no tracking pixels). A configurable 14-day retention window keeps the
phone from filling up, while messages moved into a folder are kept forever.
Five languages: Uzbek (default), English, Russian, Arabic (RTL), Korean.
Credentials live in `EncryptedSharedPreferences` behind the Android Keystore.

- **Built** — 2026-07 · **Version** — 1.0.0
- **Platforms** — Android 8+ (minSDK 26) · package `uz.jumanazar.nurmail`
- **Stack** — Kotlin, Jetpack Compose
- **Download** — [NurMail-v1.0.0.apk](../../releases/download/nurmail-v1.0.0/NurMail-v1.0.0.apk) — ~13 MB, signed release build.
  Gmail/Outlook/Yahoo require an app password rather than the account password.
- **Source** — private

<!-- screenshots: screenshots/nurmail/ -->

---

<a id="nurmedia"></a>
## NurMedia — cross-platform video trimmer

<img src="assets/nurmedia.png" alt="NurMedia icon" width="96" align="right">

Open a 40–60 minute video and cut it into short clips with a real editor
timeline. Built on a modular shell with a shared job runner that drives
`ffmpeg`/`ffprobe` natively, so long exports stay responsive and cancellable.

- **Built** — 2026-07
- **Platforms** — Windows, Linux, macOS (Apple Silicon)
- **Stack** — Tauri v2, Rust, ffmpeg/ffprobe
- **Download** — [Windows installer (.exe)](../../releases/download/nurmedia-v0.1.0/NurMedia_0.1.0_x64-setup.exe) ·
  [MSI](../../releases/download/nurmedia-v0.1.0/NurMedia_0.1.0_x64_en-US.msi) — v0.1.0, ~2 MB
  (requires `ffmpeg` and `ffprobe` on PATH)
- **Source** — private

<!-- screenshots: screenshots/nurmedia/ -->

---

<a id="http-client"></a>
## HTTP Client — native Windows request client

<img src="assets/http-client.png" alt="HTTP Client icon" width="96" align="right">

A Postman-lite desktop client. A Rust backend makes the real HTTP calls via
`reqwest` while a static frontend renders in the system WebView2 — no CORS, no
bundled browser, near-instant startup. Method, URL, editable header rows and
JSON body; responses show color-coded status, timing, size, collapsible headers
and pretty-printed JSON.

- **Built** — 2026-07
- **Platforms** — Windows
- **Stack** — Tauri v2, Rust (`reqwest`), WebView2
- **Download** — [Windows installer (.exe)](../../releases/download/http-client-v0.1.0/HTTP-Client_0.1.0_x64-setup.exe) — v0.1.0, ~2 MB
- **Source** — private

<!-- screenshots: screenshots/http-client/ -->

---

<a id="nurly"></a>
## Nurly — Android short-video maker

Turns images and audio into short vertical videos. Pick up to 30 images,
reorder them and set each slide's duration, add background music clipped to
length, and choose a 9:16, 1:1 or 16:9 canvas. Live preview runs through
`CompositionPlayer` on the *same* composition the exporter muxes — so what you
preview is what you export, not an approximation. Exports to MP4 with progress,
then saves to the gallery or shares. Uzbek is the default language, English a
translation.

- **Built** — 2026-07 · **Version** — 0.1.14
- **Platforms** — Android 8+ (minSDK 26) · package `uz.jumanazar.nurly`
- **Stack** — Kotlin, Jetpack Compose, Media3 Transformer
- **Download** — [nurly-0.1.14.apk](../../releases/download/nurly-v0.1.14/nurly-0.1.14.apk) — ~11 MB, signed release build.
  Sideloading needs "install from unknown sources" enabled.
- **Source** — private

<!-- screenshots: screenshots/nurly/ -->

---

<a id="nur-player"></a>
## Nur Player — Android media player

Plays the audio already on your device. Tracks are read straight from
MediaStore — filtered to real music, not notification blips — with folder,
artist and genre filters to narrow the list. No account, no library import, no
sync.

Playback runs in a foreground service that survives leaving the app: transport
controls in the notification and on the lock screen backed by a
`MediaSessionCompat`, a queue with next/previous, 10-second skip forward and
back, and media-button handling so play/pause from Bluetooth or wired earbuds
keeps working after the app is swiped away.

- **Built** — 2025-09 → 2026-07 · **Version** — 1.0
- **Platforms** — Android 10+ (minSDK 29, targets SDK 36) · package `uz.jumanazar.nurplayer`
- **Stack** — Java, AndroidX Media (`MediaSessionCompat`), Navigation component
- **Download** — [NurPlayer-v1.0-release.apk](../../releases/download/nur-player-v1.0/NurPlayer-v1.0-release.apk) — ~11 MB, signed release build.
  Sideloading needs "install from unknown sources" enabled for your browser or file manager.
- **Source** — private

<!-- screenshots: screenshots/nur-player/ -->

---

<a id="yuklabbar"></a>
## YuklabBar — Telegram video/MP3 downloader

Public Telegram bot: send a link, get the video or an MP3 back in the chat.
Built on a Python download pipeline (`yt-dlp`) behind a FastAPI service, with
optional start/end trimming so you can pull just a section of a long video.

- **Built** — 2022 → present (live)
- **Stack** — Python, yt-dlp, FastAPI
- **Use it** — [@yuklabbar_bot](https://t.me/yuklabbar_bot)

---

<a id="chiptachi"></a>
## Damir Yo'l Chiptachi — Telegram train ticket bot

Searches, books and pays for **eticket.railway.uz** train tickets from inside
Telegram. Multi-tenant: each user runs `/setup` once to store — encrypted —
their own railway.uz login, passenger identity and card. Then they search a
route and date, get every train with live seat counts and fares per class, pick
one, confirm the OTP from their bank SMS in the chat, and the e-ticket PDF
comes back in the same conversation.

Train search needs no setup at all: railway.uz validates CSRF by double-submit,
so the bot mints its own token and queries the timetable with no browser, no
login and no cookie export. Booking and payment run on a short-lived JWT from
the user's own login, with transient-failure handling designed so a retry can
never double-charge.

> **Status: running in test mode (test rejim).** The full search → book → pay →
> OTP → PDF flow works end to end, but it is not yet open for general public
> use.

- **Built** — 2026
- **Stack** — Node.js, Telegram Bot API, encrypted per-user credential store
- **Use it** — [@damiryolchiptachi_bot](https://t.me/damiryolchiptachi_bot)
- **Source** — private

<p>
  <img src="screenshots/damiryolchiptachi_bot/search results.png" width="46%" alt="Search results with seat counts and fares">
  <img src="screenshots/damiryolchiptachi_bot/e-ticket payment_booking_confirmation.jpg" width="26%" alt="OTP confirmation and ticket delivery">
  <img src="screenshots/damiryolchiptachi_bot/e-ticket.jpg" width="26%" alt="Delivered e-ticket PDF">
</p>

---

<a id="arabic-learning-platform"></a>
## jumanazar.uz — Arabic learning + personal tools platform

Started as a web platform for learning Arabic — dictionary, word lists and
tests, localized in Uzbek and Arabic — and grew into a personal toolbox around
it, all behind one account:

- **Arabic dictionary & tests** — word entries, lists and self-testing.
- **Debt tracker** — money owed in both directions, per person and per
  currency (KRW and USD held separately, never summed across rates), with
  running balances, repayment due dates and a breakdown chart.
- **Monthly expense manager** — expenses by category and month with a total
  and a category breakdown chart, entered in the currency of your choice.
- **Overtime & wage calculator** — computes extra-hours pay under the **Korean
  labour system**. Rest days come from the user's contracted work days, and
  public holidays are detected automatically through the data.go.kr holiday
  API, including the lunar-calendar ones (설날, 추석, 부처님오신날) and
  substitute holidays. The integration is optional by design: without a key the
  API reports that the lookup is unavailable rather than silently returning an
  empty holiday list, and the user ticks rest days by hand.
- **Utilities** — media downloader and a GitHub repository manager.

The Angular frontend is deployed on Vercel; the Node.js/MongoDB REST backend
with JWT authentication runs on Render.

- **Built** — 2023-12 → present (actively maintained)
- **Stack** — Angular (TypeScript) · Node.js, MongoDB, JWT · data.go.kr holiday API
- **Links** — live: [jumanazar.uz](https://jumanazar.uz)

<p>
  <img src="screenshots/jumanazar/overtime-tracker.png" width="47%" alt="Overtime tracker: monthly hours, paid vs unpaid overtime, per-day log">
  <img src="screenshots/jumanazar/debt-tracker.png" width="47%" alt="Debt tracker: balances per person and currency">
</p>
<p>
  <img src="screenshots/jumanazar/expenses.png" width="60%" alt="Monthly expense manager with category breakdown">
</p>

<sub>Figures and personal names in these screenshots are redacted.</sub>

---

# Other personal projects

Public repositories on [github.com/jsr1611](https://github.com/jsr1611) —
smaller apps, experiments and coursework, grouped by area. Forks and
boilerplate starters are omitted.

### Backend & APIs — Java / Kotlin / Spring

| Project | Year | What it is |
|---|---|---|
| [wallet_transfer_api](https://github.com/jsr1611/wallet_transfer_api) | 2026 | Wallet-to-wallet money transfer REST API |
| [houzing-app](https://github.com/jsr1611/houzing-app) | 2023 | Real-estate listing application |
| [StudentInfoSystem](https://github.com/jsr1611/StudentInfoSystem) | 2023 | Student information management system |

### Web & frontend

| Project | Year | What it is |
|---|---|---|
| [jsr1611.github.io](https://github.com/jsr1611/jsr1611.github.io) | 2024 | Personal web page |
| [Move-Planner-App](https://github.com/jsr1611/Move-Planner-App) | 2023 | Moving planner in vanilla JS with jQuery + AJAX |
| [zoom](https://github.com/jsr1611/zoom) | 2022 | Video-call app experiment |

### Desktop, IoT & industrial data

| Project | Year | What it is |
|---|---|---|
| [Sensor-Management-Application](https://github.com/jsr1611/Sensor-Management-Application) | 2026 | Modbus RTU collector for temperature, humidity and particle data into MS SQL |
| [VisualizerApp_CSharp_Winform](https://github.com/jsr1611/VisualizerApp_CSharp_Winform) | 2021 | WinForms visualizer for sensor data in MS SQL |
| [CrossPlatformDataCollectorApp](https://github.com/jsr1611/CrossPlatformDataCollectorApp) | 2021 | Cross-platform data collection client |

### Android

| Project | Year | What it is |
|---|---|---|
| [KirimChiqim](https://github.com/jsr1611/KirimChiqim) | 2023 | Personal income/expense tracker |

### Python, ML & computer vision

| Project | Year | What it is |
|---|---|---|
| [Thumbnail_Generator_Py](https://github.com/jsr1611/Thumbnail_Generator_Py) | 2022 | Generates thumbnails from videos stored in MySQL |
| [ImgProc](https://github.com/jsr1611/ImgProc) | 2020 | Image processing with C++ and Qt |
| [django-app](https://github.com/jsr1611/django-app) · [django-pagesapp](https://github.com/jsr1611/django-pagesapp) | 2022 | Django web app experiments |

### Algorithms & practice

| Project | Year | What it is |
|---|---|---|
| [DS-and-Algo-Practice](https://github.com/jsr1611/DS-and-Algo-Practice) | 2026 | Data structures and algorithms practice |
| [Java-Practice](https://github.com/jsr1611/Java-Practice) | 2023 | Java, web and DBMS concepts for interviews |
| [JavaPracticeSolutions](https://github.com/jsr1611/JavaPracticeSolutions) | 2021 | General Java / DSA solutions |
| [Data-Structures-And-Algorithms-Udacity](https://github.com/jsr1611/Data-Structures-And-Algorithms-Udacity) | 2021 | Udacity DSA nanodegree solutions |
| [OOP-practice](https://github.com/jsr1611/OOP-practice) | 2020 | OOP fundamentals in C# |
| [c-programming-practice](https://github.com/jsr1611/c-programming-practice) | 2020 | C programming practice |

---

## Tech I work with

**Desktop** Tauri v2, Rust · **Mobile** Kotlin, Jetpack Compose ·
**Web** Angular, React, TypeScript · **Backend** Node.js, Spring Boot, Java,
Python · **Data** MongoDB, PostgreSQL · **Media** ffmpeg, Media3

**AI / LLM integration** — Claude, ChatGPT, Gemini, Qwen and other hosted
models, plus self-hosted models via Ollama for on-premise and privacy-sensitive
workloads. Prompt design, structured/tool-calling output, retrieval over
enterprise documents, and wiring all of it into existing backend services.
