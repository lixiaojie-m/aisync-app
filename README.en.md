<p align="center">
  <img src="./assets/logo.png" width="88" alt="AISync logo" />
</p>

<h1 align="center">AISync</h1>

<p align="center"><strong>Your team's AI skill library — manage once, use anywhere.</strong></p>

<p align="center">
  <a href="https://www.aisync.work/">Website</a> ·
  <a href="https://www.aisync.work/#download">Download</a> ·
  <a href="https://www.aisync.work/install-help">Install help</a> ·
  <a href="./README.md">简体中文</a>
</p>

<p align="center">
  <img src="./assets/og-image.png" alt="AISync — your team's AI skill library" width="100%" />
</p>

## What is AISync

AISync is a **local-first AI skill manager for teams**. It brings the Agent Skills scattered across Claude Code, Cursor, Codex, ZCode, and other tools into one manageable asset: discover local skills, keep versions and sources consistent, install them into any supported tool or project, and share them with your team.

**Manage once, use anywhere.**

> This repository is the product introduction and entry point. The desktop client and server source code are not public.

<p align="center">
  <img src="./assets/homepage.png" alt="AISync homepage" width="100%" />
</p>

## Why AISync

- The same skill lives in Claude Code, Cursor, Codex, and other tools — versions drift.
- Team members run different versions and share skills through chat.
- Switching machines or tools means finding and reinstalling everything.
- It is hard to see which skills exist locally and which version the team is on.

AISync turns this into one flow: **discover → upload → version → install → share**.

## Features

| Feature | What it does |
| --- | --- |
| Local skill discovery | Scans each tool's user-level and project skill directories |
| Install to tools / projects | Installs into any supported tool or project, with overwrite confirmation and rollback |
| Personal space | Uploads skills to a personal cloud space with immutable versions, history, and rollback |
| Team space | Creates a team, invites members, publishes skills, and lets members install on demand |
| Share install links | Generates 24-hour install links for a specific version |
| Version management | Every upload creates an immutable version with history and rollback |
| Content moderation | Scans skill content before upload and publish, blocking high-risk content |
| Multilingual | Simplified Chinese, English, Japanese, Korean, and more |
| Auto update | Checks for updates, verifies signatures, and lets the user confirm the restart |

## Supported tools

AISync ships with 24 tool adapters:

Claude Code, Codex, Gemini CLI, Cursor, Cline, Kilo Code, Qwen Code, Roo Code, OpenCode, Trae, Windsurf, Grok, Kimi, Qoder, CodeBuddy, Augment, Antigravity, OpenClaw, Warp, Hermes, Pi, WorkBuddy, ZCode, DeepSeek Harness.

If your tool is not on the list, open an issue and tell us.

## Download

- Website: [https://www.aisync.work](https://www.aisync.work/)
- Download: [https://www.aisync.work/#download](https://www.aisync.work/#download)
- Install help: [https://www.aisync.work/install-help](https://www.aisync.work/install-help)

Available for macOS (Apple silicon and Intel) and Windows x64.

## How it works

1. **Discover**: AISync scans the skill directories of the tools installed on your machine.
2. **Upload**: Upload a skill to your personal space as a managed version.
3. **Share**: Publish it to a team space and invite members.
4. **Install**: Members install it into their own tools or projects.
5. **Update**: New cloud versions replace local copies while keeping version history.

## Team space

![AISync team space](./assets/teams.png)

One skill, shared with the whole team:

- Skills live in a dedicated team space and are maintained together
- Members install on demand into their own tools or projects
- Clear permissions: edit vs. read-only
- Multi-device sync: no more hunting for skills on a new machine

## FAQ

**Do I need an account?**
Local scanning, installing, and organizing do not require an account. Uploading and publishing to a team space do.

**Which platforms are supported?**
macOS (Apple silicon and Intel) and Windows x64.

**How is this different from copying skills manually?**
AISync manages versions, sources, and team sharing. Each skill has a history and a clear source space, and members install on demand instead of passing files around in chat.

**Is AISync open source?**
This repository is the product introduction and entry point. The desktop client and server source code are not public.

## Links

- Website: [https://www.aisync.work](https://www.aisync.work/)
- Download: [https://www.aisync.work/#download](https://www.aisync.work/#download)
- Install help: [https://www.aisync.work/install-help](https://www.aisync.work/install-help)
- 简体中文: [README.md](./README.md)

## Feedback

Please use [Issues](https://github.com/lixiaojie-m/aisync-app/issues) for questions and suggestions.

If AISync is useful to you, a star is appreciated.

## Trademark

The AISync name and logo belong to their respective owner. This repository is for product introduction and documentation only; it does not contain the client or server source code. Do not use the AISync name, logo, or brand assets for commercial purposes without permission.
