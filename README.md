<p align="center">
  <img src="brand/cerebra-mark.svg" width="120" alt="Cerebra" />
</p>

<h1 align="center">Cerebra</h1>

<p align="center">
  <strong>An IDE for the CyberSecurity Professional</strong><br/>
  Hosts, sessions, runbooks, AI, graphs, notes, and analysis in one desktop flow.
</p>

<p align="center">
  <a href="https://cerebra.sh">Website</a> &middot;
  <a href="https://cerebra.sh/download">Download</a> &middot;
  <a href="https://github.com/user/cerebra/releases">Releases</a> &middot;
  <a href="https://github.com/user/cerebra/discussions">Discussions</a>
</p>

---

<p align="center">
  <img src="screenshots/home-hero-workspace.png" alt="Cerebra Workspace" width="900" />
</p>

## What is Cerebra?

Cerebra is a desktop application that keeps execution, evidence, enrichment, and offline analysis in one workspace so your workflow doesn't break when tasks change. It connects to hosts over **SSH**, **RDP**, **VNC**, and **local shell** — all in a single multi-pane interface with persistent tabs, split panes, and reusable templates.

### Core Pillars

- **Hosts and live sessions in one shell** — SSH, RDP, VNC and browser side by side, split-screen like a tmux master
- **Runbooks inject directly into active panes** — reusable command cards push into the live session, not disconnected notes
- **AI turns live work into reusable knowledge** — the AI Toolkit reasons over your workspace, not a detached chatbot
- **CyberViewer keeps flow graphs beside the work** — attack-flow graphs stay connected to runbooks and evidence

---

## Workflow Tools

### Runbooks

Reusable command cards that inject directly into the active shell or pane. Build once, execute everywhere — pentesting, OSCP, bug bounty, OSINT, cloud, and more.

<p align="center">
  <img src="screenshots/home-runbooks.png" alt="Runbooks" width="800" />
</p>

### Runbook Marketplace

Browse and discover community runbooks for common workflows — pentesting, offensive security, bug bounty, OSINT, network security, cloud, OSCP, CKS, CPTS, and more.

<p align="center">
  <img src="screenshots/home-runboook-marketplace.png" alt="Runbook Marketplace" width="800" />
</p>

### AI Toolkit

The AI Toolkit reasons over the live workspace — current sessions, terminal output, and operator context — instead of acting like a generic chatbot. Switch to **AI-Cyber Mode** and the AI can see and control everything: RDP, browser, SSH, intelligence tools, pentesting, graph building.

<p align="center">
  <img src="screenshots/home-ai-toolkit.png" alt="AI Toolkit" width="800" />
</p>

### CyberViewer

Attack-flow graphs stay connected to runbooks and previews so the app captures both action and structure. Visualize kill chains, pivot paths, and operational flow without leaving the workspace.

<p align="center">
  <img src="screenshots/home-cyberviewer.png" alt="CyberViewer" width="800" />
</p>

### Notes

Evidence, screenshots, code blocks, and operator notes captured in the same app. No more fragmenting across tools — everything stays beside the work.

<p align="center">
  <img src="screenshots/home-notes.png" alt="Notes" width="800" />
</p>

---

## Analysis Tools

### Intel

Enrich domains, URLs, IPs, and hashes from the same workspace without pivoting into a pile of browser tabs. Investigate indicators in-flow.

<p align="center">
  <img src="screenshots/home-intel.png" alt="Intel" width="800" />
</p>

### RevEng

Map suspicious APIs to ATT&CK, triage binaries, deobfuscate content, and extract IoCs — all in the same workspace that holds the live session.

<p align="center">
  <img src="screenshots/home-reveng.png" alt="RevEng" width="800" />
</p>

### Crypto

Decode JWTs, hash payloads, convert formats, and run utility transforms without copying data into random web tools. Quick transforms stay docked beside the shell.

<p align="center">
  <img src="screenshots/home-crypto.png" alt="Crypto" width="800" />
</p>

---

## Protocol Support

| Protocol | Description |
|----------|-------------|
| **SSH** | Real PTY-backed terminal sessions with persistent tabs and split panes |
| **RDP** | Docker-backed preferred mode with native fallback when needed |
| **VNC** | Integrated noVNC workflow inside the same workspace shell |
| **Local Shell** | Quick local sessions for drafting, testing, and operator utility work |

---

## Download

Current release: **v2.0.0**

| Platform | Arch | Format | Size | SHA-256 |
|----------|------|--------|------|---------|
| [macOS](https://downloads.cerebra.sh/releases/2.0.0/Cerebra-2.0.0-arm64-mac.zip) | Apple Silicon | ZIP | 116 MB | `06078ae8...682afe4a` |
| [Windows Installer](https://downloads.cerebra.sh/releases/2.0.0/Cerebra%20Setup%202.0.0.exe) | x64 | EXE | 92 MB | `b733c974...d1e11337` |
| [Windows Portable](https://downloads.cerebra.sh/releases/2.0.0/Cerebra%202.0.0.exe) | x64 | EXE | 92 MB | `50961f7c...46230ce` |
| [Linux AppImage](https://downloads.cerebra.sh/releases/2.0.0/Cerebra-2.0.0-x86_64.AppImage) | x64 | AppImage | 126 MB | `cff4a9e9...a2ede4d` |

> Downloads are also available at [cerebra.sh/download](https://cerebra.sh/download).

### Installation Notes

**macOS** — The build is Apple-notarized. Extract the ZIP and move Cerebra to Applications.

**Windows** — Use the installer for a standard install, or the portable EXE to run directly without installation.

**Linux** — Make the AppImage executable (`chmod +x Cerebra-*.AppImage`) and run it. AppImage support is experimental while the distro matrix is completed.

---

## Full SHA-256 Checksums

```
06078ae8dc6e154920a23febfb2cdbd495d3e3a3145ce08123638020682afe4a  Cerebra-2.0.0-arm64-mac.zip
b733c974ab54ccd38081e11ee01658bc9c8454d75bebb555c82db0efd1e11337  Cerebra Setup 2.0.0.exe
50961f7cd82f91ff8a51f52c00e9cb7db5c5b682634b9a03dffb2bcf546230ce  Cerebra 2.0.0.exe
cff4a9e920bc0a9ee5e2ebc347f6415ea6995bcdcbca960f2b49e49bea2ede4d  Cerebra-2.0.0-x86_64.AppImage
```

---

## Community

- **Bug reports** — [Open an issue](../../issues/new?template=bug_report.yml)
- **Feature requests** — [Open an issue](../../issues/new?template=feature_request.yml)
- **Discussions** — [Join the conversation](../../discussions)

---

## License

Cerebra is proprietary software. See [LICENSE](LICENSE) for details.

<p align="center">
  <a href="https://cerebra.sh">cerebra.sh</a>
</p>
