# Guardian Eye 👁️

**Privacy-first video surveillance for Windows, Linux & macOS**

> No cloud. No subscriptions. No tracking. Your footage stays on your machine.

### Product

[![Website](https://img.shields.io/badge/Website-getguardianeye.com-0969DA?style=flat-square)](https://getguardianeye.com)
[![Download](https://img.shields.io/badge/Download-Guardian_Eye-1F883D?style=flat-square)](https://getguardianeye.com/download)
[![Changelog](https://img.shields.io/badge/Changelog-What's_new-8250DF?style=flat-square)](https://getguardianeye.com/changelog)
[![Releases](https://img.shields.io/badge/GitHub-Releases-1F2328?style=flat-square&logo=github)](https://github.com/GuardianEye-Official/Guardian.Eye/releases)

### Community and support

[![Discussions](https://img.shields.io/badge/GitHub-Discussions-8250DF?style=flat-square&logo=github)](https://github.com/GuardianEye-Official/Guardian.Eye/discussions)
[![Issues](https://img.shields.io/badge/GitHub-Issues-1F883D?style=flat-square&logo=github)](https://github.com/GuardianEye-Official/Guardian.Eye/issues)
[![Reddit](https://img.shields.io/badge/Reddit-r%2FGuardianEyeApps-FF4500?style=flat-square&logo=reddit&logoColor=white)](https://www.reddit.com/r/GuardianEyeApps/)
[![X / Twitter](https://img.shields.io/badge/X-GuardianEyeApp-black?style=flat-square&logo=x)](https://x.com/GuardianEyeApp)
[![Telegram](https://img.shields.io/badge/Telegram-Guardian__Eye-2CA5E0?style=flat-square&logo=telegram)](https://t.me/Guardian_Eye)

---

## What is Guardian Eye?

Guardian Eye is a local network video recorder for Windows, Linux and macOS. It connects to ONVIF, RTSP/RTSPS and USB cameras, stores recordings on your own disks, and runs video and audio recognition on the recorder itself. No account is required.

The same application can run a small home setup or a much larger installation. Version 4.0.1 introduced a shared capture and recording pipeline designed to avoid duplicate camera connections and decoding work.

## Version 4.0.1

| Area | What changed |
|------|--------------|
| **Recording pipeline** | Each camera uses one shared capture path. Encoded packets can go directly to the archive while live view and detection reuse the same source. |
| **Large installations** | The new architecture supports installations with more than 100 cameras when the server, network and storage are sized for the workload. |
| **Synchronized player** | Review up to nine cameras at the same wall-clock time, with separate timeline lanes, event filters, marks and an independent audio source. |
| **MCP server** | Connect compatible AI assistants over Streamable HTTP. More than 100 tools cover cameras, events, recordings, PTZ, schedules, zones, storage and diagnostics. Access is controlled with scoped, revocable tokens. [Setup guide](https://getguardianeye.com/docs/integrations/mcp). |
| **Home Assistant** | Publish cameras, sensors, events, detection snapshots and controls over MQTT. The Guardian Eye component adds a dashboard with low-latency WebRTC video. [Setup guide](https://getguardianeye.com/docs/integrations/home-assistant). |
| **Local recognition** | Updated video and sound models run locally. Optional recognition includes bird species and licence plates, and sound events now include knocking. |
| **Setup and layout** | A first-run wizard covers cameras, recording, schedules, zones, storage and notifications. Camera tiles can be moved and resized, and their layout is restored on the next launch. |

[Read the 4.0.1 release notes](https://github.com/GuardianEye-Official/Guardian.Eye/releases/tag/v4.0.1)

## Main capabilities

| Capability | Details |
|------------|---------|
| **Camera support** | ONVIF, RTSP/RTSPS and USB cameras, with network discovery and PTZ controls where the camera supports them |
| **Recording** | Continuous and event-driven recording, pre-record buffer, per-camera schedules, retention limits and automatic storage cleanup |
| **Archive recovery** | ONVIF Profile G recovery and FTP/FTPS ingestion for bringing camera-side recordings into the main archive |
| **Local detection** | Motion, objects, sound and camera tampering, with inclusion and exclusion zones |
| **Notifications** | Desktop, email and Telegram alerts; MQTT events and entities for Home Assistant automations |
| **Hardware acceleration** | NVIDIA CUDA, DirectML, OpenVINO, VAAPI on Linux and Metal on macOS, with software fallback |
| **Languages** | The application and current integration UI are available in 18 languages |
| **Privacy** | Recordings and recognition stay on your computer; the application has no mandatory cloud account or telemetry |

---

## Pricing

New installations start with a 30-day Pro trial. No key, account or payment card is required for the trial.

| Plan | Price | Cameras |
|------|-------|---------|
| **Free** | $0 forever | 1 camera |
| **Home** | $29 one-time | 4 cameras |
| **Pro** | $79 one-time | Unlimited |

No subscriptions. No renewals. Pay once, use forever.

---

## Platform support

- **Windows** 10/11 x64 — signed installer (SSL.com certificate)
- **Linux** — Ubuntu 24+, Debian 13+, Fedora 43+; packages are also available through Snap
- **macOS** — 12 Monterey+ (Apple Silicon & Intel) — signed & notarized by Apple

---

## Repositories

| Repository | Description |
|------------|-------------|
| [Guardian.Eye](https://github.com/GuardianEye-Official/Guardian.Eye) | Desktop application — releases, changelogs, issue tracker |
| [.github](https://github.com/GuardianEye-Official/.github) | Organization profile |

## Resources

- 🌐 [Website](https://getguardianeye.com)
- 📥 [Download](https://getguardianeye.com/download)
- 📝 [Changelog](https://getguardianeye.com/changelog)
- 📖 [Documentation](https://getguardianeye.com/docs)
- 🔌 [MCP server guide](https://getguardianeye.com/docs/integrations/mcp)
- 🏠 [Home Assistant guide](https://getguardianeye.com/docs/integrations/home-assistant)
- 💬 [GitHub Discussions](https://github.com/GuardianEye-Official/Guardian.Eye/discussions)
- 🟠 [Reddit community](https://www.reddit.com/r/GuardianEyeApps/)
- 💬 [Telegram Community](https://t.me/Guardian_Eye)
- 📧 [Contact](mailto:info@getguardianeye.com)

---

⭐ **Star [Guardian.Eye](https://github.com/GuardianEye-Official/Guardian.Eye)** if you believe privacy matters.
