<p align="right"><a href="./README.md">English</a> · <strong>한국어</strong></p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/profile-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/profile-light.svg">
  <img alt="AICASTER — 쓸모 있는 소프트웨어를 끝까지 만듭니다. 데이터 시스템, AI 제품, 창작 도구." src="./assets/profile-dark.svg" width="100%">
</picture>

<h1 align="center">김성민 · AICASTER</h1>
<p align="center">
  <strong>데이터 엔지니어 &amp; AI와 함께 제품을 만드는 개발자</strong><br>
  Appcaster라는 이름으로도 활동합니다 · <a href="https://github.com/himomohi">@himomohi</a>
</p>
<p align="center">
  <a href="#대표-프로젝트">대표 프로젝트</a> ·
  <a href="#제가-가져오는-역량">역량</a> ·
  <a href="#오픈소스-기여">오픈소스 기여</a> ·
  <a href="#연결하기">연결하기</a>
</p>

데이터 엔지니어이자 AI와 함께 제품을 만드는 개발자입니다. 복잡한 작업 흐름을 사람들이 실제로 쓸 수 있는 소프트웨어로 바꿉니다. **데이터 엔지니어링, AI 연동, 네이티브 데스크톱 앱, 창작·개발 도구**를 넘나들며 작업합니다.

문제를 이해하고 사용 경험을 설계하는 일부터 구현, 검증, 배포, 개선까지 이어지는 전체 과정을 좋아합니다. 아이디어를 제시하는 데서 멈추지 않고, 실제로 사용할 수 있는 결과까지 만드는 것이 제 지향점입니다.

## 대표 프로젝트

<table>
<tr>
<td width="50%" valign="top">
<h3><a href="https://github.com/himomohi/AirTranslate">01 / AirTranslate</a></h3>
<p><strong>Mac에서 재생되는 소리를 실시간 자막으로.</strong></p>
<p>시스템 오디오를 받아 전사·번역하고 플로팅 자막으로 보여주는 macOS 앱입니다. Apple 프레임워크를 기본 경로로 사용하며, 선택적으로 AI 제공자와 연동합니다.</p>
<p><code>Swift</code> <code>SwiftUI</code> <code>ScreenCaptureKit</code></p>
<p><strong>보여주는 역량:</strong> 네이티브 앱 개발, 실시간 오디오 처리 흐름, 지속적인 제품 개선.</p>
<p><a href="https://himomohi.github.io/AirTranslate/">제품 안내</a> · <a href="https://github.com/himomohi/AirTranslate/releases">릴리스</a></p>
<sub>GitHub 427스타 · 45포크. 2026-09-06 확인.</sub>
</td>
<td width="50%" valign="top">
<h3><a href="https://github.com/himomohi/pixelforge-studio">02 / PixelForge Studio</a></h3>
<p><strong>사람과 AI 에이전트가 함께 쓰는 픽셀아트 작업실.</strong></p>
<p>드로잉, 레이어, 애니메이션, 팔레트, 내보내기를 제공하는 브라우저 편집기입니다. 호환 에이전트는 65개 구조화된 WebMCP 도구로 사람과 같은 프로젝트 상태를 편집합니다.</p>
<p><code>TypeScript</code> <code>React</code> <code>WebMCP</code></p>
<p><strong>보여주는 역량:</strong> 인터랙티브 제품 설계, 편집 상태 공유, 구조화된 에이전트 도구 연동.</p>
<p><a href="https://pixelforge-studio.himomohi.workers.dev">편집기 열기</a> · <a href="https://github.com/himomohi/pixelforge-studio">소스와 데모</a></p>
<sub>브라우저 기반 창작 도구 · 사람이 확인하고 이어갈 수 있는 편집.</sub>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3><a href="https://github.com/himomohi/codex-pet-hud">03 / Codex Pet HUD</a></h3>
<p><strong>개발 도구에 작은 게임의 재미를 더합니다.</strong></p>
<p>Codex 사용량을 데스크톱 펫 옆의 물약 게이지로 표현하는 HUD입니다. 초기화까지 남은 시간과 플랫폼별 네이티브 제어 기능을 제공합니다.</p>
<p><code>Swift / AppKit</code> <code>.NET / WPF</code></p>
<p><strong>보여주는 역량:</strong> 크로스플랫폼 데스크톱 연동, 작은 제품의 UX, 게임 감각을 살린 정보 표현.</p>
<p><a href="https://himomohi.github.io/codex-pet-hud/">제품 사이트</a> · <a href="https://github.com/himomohi/codex-pet-hud">소스</a></p>
<sub>macOS · Windows 프리뷰. Windows 실기기 UI 검증은 아직 남아 있습니다.</sub>
</td>
<td width="50%" valign="top">
<h3><a href="https://github.com/himomohi/love2d-mcp">04 / LÖVE2D MCP</a></h3>
<p><strong>에이전트가 게임 안에서 확인하고 다시 시도하도록.</strong></p>
<p>게임 상태 조회, 가상 입력, 시뮬레이션 단계 진행, 화면 캡처, 스냅샷 비교를 연결하는 런타임 도구입니다.</p>
<p><code>TypeScript</code> <code>Lua</code> <code>MCP</code></p>
<p><strong>보여주는 역량:</strong> 도구 프로토콜 연동, 실행 상태 관찰, 화면 기반 플레이 테스트 흐름.</p>
<p><a href="https://github.com/himomohi/love2d-mcp">도구와 예제</a> · <a href="https://github.com/shayarnett/love2d-mcp">원본 프로젝트</a></p>
<sub>shayarnett/love2d-mcp의 포크 확장판이며 원작자 기여를 명시합니다.</sub>
</td>
</tr>
</table>

## 제가 가져오는 역량

**데이터에서 실제로 사용할 수 있는 제품까지 연결합니다.** 데이터 변환과 자동화를 사람이 이해하기 쉬운 인터페이스로 이어갑니다. 명확한 입력, 확인 가능한 실패, 실용적인 상호작용, 사용할 수 있는 결과까지 전체 흐름을 중요하게 생각합니다.

| 영역 | 사용하는 도구 | 실제로 연결하는 일 |
| :--- | :--- | :--- |
| **데이터·자동화** | Python, pandas, SQL, MySQL, MongoDB | 데이터 변환, 검증, 반복 작업 자동화. |
| **웹 제품** | TypeScript, JavaScript, React, Tailwind CSS, Node.js, FastAPI | 인터랙티브 화면과 그 뒤의 서비스 구현. |
| **네이티브 데스크톱** | Swift, SwiftUI, AppKit, .NET/WPF, PowerShell | 오디오 처리 흐름, 오버레이, 메뉴바·트레이 유틸리티. |
| **AI·창작 도구** | MCP, WebMCP, Codex, Claude Code, Lua, LÖVE | 구조화된 도구, 에이전트 협업, 게임 개발 실험. |
| **배포·품질** | Git, GitHub Actions, Playwright, 집중 회귀 테스트 | 검토 가능한 변경, 재현 가능한 검사, 배포 안내, 한계 명시. |

## 오픈소스 기여

제 저장소 밖의 코드베이스에도 기여합니다. 아래 기록은 **원본 저장소에 실제 병합된 코드**, **현재 리뷰 중인 제안**, **제가 유지하는 포크 확장**을 구분해 상태를 과장하지 않도록 정리했습니다.

### 원본 저장소에 병합된 기여

| 프로젝트 | 실제 반영된 기여 | 공개 기록 |
| :--- | :--- | :--- |
| **OpenCodex** | Windows 시작 안전성 진단, 네이티브 트레이 컨트롤러, 설치·업데이트 시 수명주기 안전 처리, 관리 UI/API를 추가했습니다. 병합 PR은 54개 파일에 걸쳐 Windows 수명주기·보안·CLI·UI 검증을 포함합니다. | [병합 PR #306](https://github.com/lidge-jun/opencodex/pull/306) |
| **Orca** | 모바일 RPC가 반쯤 끊긴 WebSocket에서 수신이 멈추고 `onclose`도 오지 않을 때 정상 복구하도록 수정했습니다. 재연결 폭주 없이 하나의 대체 연결만 만들어지는지 확인하는 결정적 회귀 테스트도 추가했습니다. | [병합 PR #11368](https://github.com/stablyai/orca/pull/11368) |
| **Paseo** | 기존 번역자의 공로를 유지하면서 1,603개 영어 키와 대응되는 한국어 UI, 로케일 해석, 언어 전환, 크로스플랫폼 리소스 등록을 통합했습니다. | [병합 PR #2895](https://github.com/getpaseo/paseo/pull/2895) |

### 현재 리뷰 중인 upstream 기여

아래는 제가 공개적으로 제출한 기여이지만 **아직 병합된 작업처럼 소개하지 않습니다.**

| 프로젝트 | 제안 내용 | 현재 상태 |
| :--- | :--- | :--- |
| **Orca** | 모바일 터미널에 선택형 **더블탭 → Tab** 단축 동작을 추가하고, 스크롤·링크·TUI 탭 등 기존 제스처와 충돌하지 않도록 취소 규칙, 터미널 수명주기 초기화, 설정 저장, 집중 회귀 테스트를 구현했습니다. | [PR #10239](https://github.com/stablyai/orca/pull/10239) — open |
| **Delta** | 834개 런타임 문자열과 storyboard/XIB 리소스, Xcode 리소스 등록, Swift 문자열 추출, 남아 있던 하드코딩 UI까지 포함한 1차 한국어 현지화를 추가했습니다. | [PR #554](https://github.com/rileytestut/Delta/pull/554) — draft; 정적 검증 완료, 런타임 검증 대기 |
| **oh-my-pi** | 공식 Provider API를 사용하는 Command Code 제공자를 추가했습니다. 모델 검색, API 키 로그인, Anthropic Messages와 OpenAI 호환 Chat Completions를 모델 종류에 맞춰 나누는 라우팅과 테스트를 포함합니다. | [PR #9564](https://github.com/can1357/oh-my-pi/pull/9564) — open |

### 유지 중인 포크 확장

| 프로젝트 | 확장한 내용 |
| :--- | :--- |
| **Aseprite MCP Tools** | 원본의 104개 Aseprite 도구를 유지하면서 WebSocket Live Bridge를 결합해 생성된 편집 명령을 실행 중인 Aseprite UI에 전달하고, CLI fallback과 두 원본 프로젝트의 기여자 표기를 함께 보존했습니다. [포크 PR #1](https://github.com/himomohi/aseprite-mcp/pull/1) |
| **LÖVE2D MCP** | 원본 PoC를 보안 기본값을 갖춘 로컬 브리지로 확장했습니다. loopback 제한, 공유 토큰 인증, 제한된 선택형 Lua 실행, 요청 한계, Zod 검증, 회귀 테스트, 게임이 명시적으로 허용하는 상태 변경 API를 추가했습니다. [포크 PR #1](https://github.com/himomohi/love2d-mcp/pull/1) |

### 공개 제품 피드백

- **OpenAI Codex** — 실시간 음성 모드에서 사용자의 발화가 끝난 뒤 조용히 처리 중인 상태를 명확히 알릴 수 있도록, 접근성과 상태 중복 방지·테스트 기준을 포함한 짧은 처리 신호를 제안했습니다. [Issue #35082](https://github.com/openai/codex/issues/35082) — open.

<details>
<summary>과거에 종료된 upstream 제안</summary>

- **HashLips Art Engine** — 한국어 README 번역. [PR #1631](https://github.com/HashLips/hashlips_art_engine/pull/1631)은 2025년에 병합 없이 종료되었기 때문에 실제 반영된 기여가 아니라 과거 공개 기여 활동으로만 구분해 둡니다.

</details>

직접 만든 제품, 포크 확장, 리뷰 중인 제안, 원본 저장소에 병합된 기여는 서로 다른 작업입니다. 소개할 때도 이 경계를 분명히 구분합니다.

## 만드는 방식

> 작업 흐름 이해 → 쓸모 있는 구현 → 위험한 부분 검증 → 배포 → 개선.

**AI는 판단을 대신하는 존재가 아니라 함께 만드는 개발 파트너입니다.** 조사, 구현, 반복 개선에 활용하되 요구사항 확인, 변경 검토, 결과 검증을 함께 수행합니다.

**올바른 길을 가장 쉬운 길로 만듭니다.** 반복되는 주의 문구나 과도한 추상화, 거대한 테스트 체계보다 명확한 모듈 경계와 작고 신뢰할 수 있는 예방 장치를 선호합니다.

에이전트와 함께하는 개발, 절차적 2D 게임, 픽셀아트 제작 과정, 복잡한 작업을 더 쉽게 만드는 도구에 꾸준히 관심을 갖고 있습니다.

## 연결하기

실용적인 AI 제품, 개발 도구, 데이터 작업 흐름, 창작 소프트웨어에 관한 아이디어를 나누는 것을 좋아합니다.

[GitHub](https://github.com/himomohi) · [X / @himomohi](https://x.com/himomohi) · [Threads / @appcast](https://www.threads.com/@appcast)

---
<sub>공개 프로젝트 정보·지표·PR 상태·이슈 상태 확인일: 2026-09-06. 수치는 해당 날짜의 기록이며 실시간 카운터가 아닙니다.</sub>
