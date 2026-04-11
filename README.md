# PandaStudio Releases

This repository hosts the signed installer binaries and auto-update
manifests for [PandaStudio](https://writepanda.ai).

**The source code lives in a private repository.** This repo exists
purely as a public download host so the landing page and
`electron-updater` can fetch releases without authentication.

Every release is:

- **macOS**: code-signed with an Apple Developer ID and notarized via
  Apple's `notarytool`
- **Windows**: signed via Azure Trusted Signing

Downloads are also available from the [writepanda.ai landing page](https://writepanda.ai/#download).
