# VaeltrixAI

VaeltrixAI is an independent AI workspace for conversation, writing, analysis, and exploration.

Built by **RajaCoders** / **VaeltrixLabs**.

[Website](https://vaeltrix-ai.vercel.app) · [Discord](https://discord.gg/WEeevnd9c) · [TikTok](https://tiktok.com/@vaeltrixai) · [X](https://x.com/vaeltrixai)

---

## Overview

VaeltrixAI is a web-based AI assistant designed to run efficiently on a wide range of devices, from entry-level phones to desktops. It is distributed as a Progressive Web App (PWA) and can be installed directly to the home screen.

The product prioritizes speed, accessibility, and practical utility over unnecessary complexity.

---

## History

**Early development**  
VaeltrixAI began as a personal project by RajaCoders. The first version was built with pure Vanilla JavaScript, no framework, and no build step, with a strong focus on performance on low-end devices.

**Open-source phase**  
An early version of the source code was made public to gather feedback and observe real usage patterns.

**Transition to closed source**  
As the system grew in complexity—particularly around security, infrastructure, and long-term sustainability—the project was moved to closed source. The previous public repository has been removed.

**Current version (2026)**  
The product underwent a full rebuild. The architecture was redesigned around a clear separation between a modular frontend and a dedicated backend gateway responsible for request handling, orchestration, and security.

---

## Design Principles

- Accessibility across devices and network conditions
- Low latency and responsive interaction
- Independent development and operational control
- Selective transparency: useful information is shared, internal implementation details are not
- Focus on features that serve real work

---

## Capabilities

- Multiple operating modes for different tasks (speed, reasoning, code, research, vision)
- Streaming responses
- Persistent memory and adjustable persona
- Project / workspace organization
- File and image attachments
- Voice input and output
- Account and credit system
- Installable as a Progressive Web App

---

## Architecture

VaeltrixAI separates the user interface from the AI orchestration layer.

```
User Device (Browser / PWA)
        │
        ▼
VaeltrixAI Frontend
  - Chat interface and streaming
  - Session and local state
  - Authentication, profile, and credits
  - History and project management
        │
        ▼
VaeltrixAI Backend Gateway
  - Request validation and rate limiting
  - Model routing and orchestration
  - Response normalization
  - Security controls
```

The frontend focuses on user experience.  
The backend focuses on orchestration, security, and control.  
Internal implementation details are proprietary.

---

## Status

|                    |                          |
|--------------------|--------------------------|
| Source code        | Closed source            |
| License            | Proprietary              |
| Public repository  | Showcase and docs only   |
| Development        | Active                   |
| Website            | [vaeltrix-ai.vercel.app](https://vaeltrix-ai.vercel.app) |
| Community          | [Discord](https://discord.gg/WEeevnd9c) |

---

## Links

- Website: https://vaeltrix-ai.vercel.app  
- Discord: https://discord.gg/WEeevnd9c  
- GitHub: https://github.com/vaeltrix  
- TikTok: https://tiktok.com/@vaeltrixai  
- X: https://x.com/vaeltrixai  
- Telegram: https://t.me/vaeltrixai  
- Email: vaeltrixteam@gmail.com

---

## About

**RajaCoders**  
Founder, VaeltrixLabs  
Creator of VaeltrixAI

VaeltrixLabs is an independent organization focused on practical, accessible AI products.

---

This document is intentionally high-level.  
Implementation details, internal architecture, and infrastructure are proprietary to VaeltrixLabs.
