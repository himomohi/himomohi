<p align="right"><strong>English</strong> · <a href="./README.ko.md">한국어</a></p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/profile-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/profile-light.svg">
  <img alt="AICASTER — Useful software. Built all the way. Data systems, AI products, creative tools." src="./assets/profile-dark.svg" width="100%">
</picture>

<h1 align="center">AICASTER · Appcaster</h1>
<p align="center">
  <strong>Data Engineer &amp; AI-native Product Builder</strong><br>
  Building as Appcaster · <a href="https://github.com/himomohi">@himomohi</a>
</p>
<p align="center">
  <a href="#selected-work">Selected work</a> ·
  <a href="#what-i-bring">Capabilities</a> ·
  <a href="#open-source-contributions">Contributions</a> ·
  <a href="#connect">Connect</a>
</p>

I'm a data engineer and an AI-native product builder. I turn complicated workflows into software people can actually use. My work spans **data engineering, AI integrations, native desktop apps, and creative developer tools**.

I like the whole journey: understanding the problem, shaping the experience, implementing it, and staying with it through testing, release, and improvement.

## Selected work

<table>
<tr>
<td width="50%" valign="top">
<h3><a href="https://github.com/himomohi/AirTranslate">01 / AirTranslate</a></h3>
<p><strong>Live captions for whatever your Mac is playing.</strong></p>
<p>A macOS app for system-audio transcription, translation, and floating captions. Apple frameworks provide the default path, with optional AI-provider integrations.</p>
<p><code>Swift</code> <code>SwiftUI</code> <code>ScreenCaptureKit</code></p>
<p><strong>What it shows:</strong> native app development, real-time audio workflows, and ongoing product iteration.</p>
<p><a href="https://himomohi.github.io/AirTranslate/">Product guide</a> · <a href="https://github.com/himomohi/AirTranslate/releases">Releases</a></p>
<sub>427 stars · 45 forks on GitHub, checked 2026-09-06.</sub>
</td>
<td width="50%" valign="top">
<h3><a href="https://github.com/himomohi/pixelforge-studio">02 / PixelForge Studio</a></h3>
<p><strong>A pixel-art workspace for people and AI agents.</strong></p>
<p>A browser editor with drawing, layers, animation, palettes, and exports. Compatible agents use 65 structured WebMCP tools to work on the same project state as the person.</p>
<p><code>TypeScript</code> <code>React</code> <code>WebMCP</code></p>
<p><strong>What it shows:</strong> interactive product design, shared editing state, and structured agent-tool integration.</p>
<p><a href="https://pixelforge-studio.himomohi.workers.dev">Open editor</a> · <a href="https://github.com/himomohi/pixelforge-studio">Source &amp; demo</a></p>
<sub>Browser-based creative tooling · human-reviewable edits.</sub>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3><a href="https://github.com/himomohi/codex-pet-hud">03 / Codex Pet HUD</a></h3>
<p><strong>Developer utility, with a little game feel.</strong></p>
<p>A companion HUD that turns Codex usage windows into potion meters beside the desktop pet, with reset countdowns and native desktop controls.</p>
<p><code>Swift / AppKit</code> <code>.NET / WPF</code></p>
<p><strong>What it shows:</strong> cross-platform desktop integration, small-product UX, and playful information design.</p>
<p><a href="https://himomohi.github.io/codex-pet-hud/">Product site</a> · <a href="https://github.com/himomohi/codex-pet-hud">Source</a></p>
<sub>macOS · Windows preview; real-device Windows UI validation remains pending.</sub>
</td>
<td width="50%" valign="top">
<h3><a href="https://github.com/himomohi/love2d-mcp">04 / LÖVE2D MCP</a></h3>
<p><strong>Give an agent a feedback loop inside a game.</strong></p>
<p>A runtime toolkit for inspecting game state, driving virtual input, stepping the simulation, capturing frames, and comparing snapshots.</p>
<p><code>TypeScript</code> <code>Lua</code> <code>MCP</code></p>
<p><strong>What it shows:</strong> tool-protocol integration, runtime observability, and visual playtesting workflows.</p>
<p><a href="https://github.com/himomohi/love2d-mcp">Toolkit &amp; examples</a> · <a href="https://github.com/shayarnett/love2d-mcp">Original project</a></p>
<sub>Fork extension of shayarnett/love2d-mcp; upstream credit preserved.</sub>
</td>
</tr>
</table>

## What I bring

**From data to a usable product.** I connect data transformation and automation with interfaces people can understand. My focus is the complete workflow: clear inputs, visible failures, practical interactions, and a result that is ready to use.

| Area | Tools I work with | How I apply them |
| :--- | :--- | :--- |
| **Data & automation** | Python, pandas, SQL, MySQL, MongoDB | Data transformation, validation, and repetitive-task automation. |
| **Web products** | TypeScript, JavaScript, React, Tailwind CSS, Node.js, FastAPI | Interactive interfaces and the services behind them. |
| **Native desktop** | Swift, SwiftUI, AppKit, .NET/WPF, PowerShell | Audio workflows, overlays, menu-bar and tray utilities. |
| **AI & creative tooling** | MCP, WebMCP, Codex, Claude Code, Lua, LÖVE | Structured tools, agent-assisted workflows, and game-development experiments. |
| **Delivery & quality** | Git, GitHub Actions, Playwright, focused regression tests | Reviewable changes, reproducible checks, release guides, and documented limits. |

## Open-source contributions

I also work in other people's codebases. These contributions were **merged upstream**:

| Project | Contribution | Public record |
| :--- | :--- | :--- |
| **Paseo** | Integrated a 1,603-key Korean locale with resource-parity and browser language-switch coverage, building on an earlier community translation and preserving its contributor's credit. | [Merged PR #2895](https://github.com/getpaseo/paseo/pull/2895) |
| **Orca** | Fixed mobile WebSocket recovery when a close event never arrives, with a deterministic regression test for the stuck-connection case. | [Merged PR #11368](https://github.com/stablyai/orca/pull/11368) |

Original products, fork extensions, and upstream contributions are different kinds of work. I keep that distinction explicit.

## How I build

> Understand the workflow → build something useful → test the risky parts → ship → improve.

**AI is a development partner, not a substitute for judgment.** I use it to explore, implement, and iterate while keeping requirements, reviews, and verification in the loop.

**Make the right path the easy path.** I prefer clear module boundaries and small, reliable safeguards over repeated warnings, unnecessary abstraction, or oversized test systems.

My recurring interests are agent-assisted development, procedural 2D games, pixel-art pipelines, and tools that make complex work feel simpler.

## Connect

I enjoy exchanging ideas about practical AI products, developer tooling, data workflows, and creative software.

[GitHub](https://github.com/himomohi) · [X / @himomohi](https://x.com/himomohi) · [Threads / @appcast](https://www.threads.com/@appcast)

---
<sub>Public project details, metrics, and merged-PR status reviewed on 2026-09-06. Metrics are a dated snapshot, not live counters.</sub>
