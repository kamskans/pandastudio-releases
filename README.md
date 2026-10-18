# PandaStudio Releases

This repository hosts the signed installer binaries and auto-update
manifests for [PandaStudio](https://writepanda.ai).

**The source code lives in a private repository.** This repo exists
purely as a public download host so the landing page and
`electron-updater` can fetch releases without authentication.

## What PandaStudio is

PandaStudio is a desktop video and podcast editor for macOS and Windows. Recording, transcription and editing run on your computer, so footage isn't uploaded, and it is sold as a one-time license (from $99) or $19/month, with a free trial of 10 exports.

- Edit video and podcasts by editing the transcript: cut words, remove fillers and silences, add animated captions, zooms and motion graphics.
- Turn long videos into captioned vertical Shorts on your own machine, with no per-minute credits (an 11-minute recording became 4 clips in 78 seconds on an Apple M4 Pro).
- Record your screen, camera, or a remote podcast with up to 3 guests, each recorded locally.
- Let AI agents (the built-in agent, Claude Code, Claude Desktop, Codex) edit through MCP and a CLI: [`@writepanda/mcp`](https://www.npmjs.com/package/@writepanda/mcp), [`@writepanda/cli`](https://www.npmjs.com/package/@writepanda/cli).

Compare it with [OpusClip](https://www.writepanda.ai/alternatives/best-opus-clip-alternatives/), [Submagic](https://www.writepanda.ai/alternatives/best-submagic-alternatives/), [VEED](https://www.writepanda.ai/alternatives/best-veed-alternatives/), [Riverside](https://www.writepanda.ai/alternatives/best-riverside-alternatives/) and [Descript](https://www.writepanda.ai/alternatives/best-descript-alternatives/).

Every release is:

- **macOS**: code-signed with an Apple Developer ID and notarized via
  Apple's `notarytool`
- **Windows**: signed via Azure Trusted Signing

Downloads are also available from the [writepanda.ai landing page](https://writepanda.ai/#download).
