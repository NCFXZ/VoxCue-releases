# VoxCue

[简体中文](README.md) | English

This repository distributes VoxCue installers, model resources, and automatic-update files.

VoxCue is a desktop interview preparation assistant for Windows and macOS. Prepare using your résumé and job description, build interview skills, and review sessions with live transcription, AI answers, and interview history.

[User guide](https://voxcue.com.cn/install/) · [Downloads and updates](https://github.com/NCFXZ/VoxCue-releases/releases) · [Report an issue](https://github.com/NCFXZ/VoxCue-releases/issues)

## Download

| Platform | Current installer | Requirements |
| --- | --- | --- |
| Windows | [0.6.7 · x64 EXE](https://github.com/NCFXZ/VoxCue-releases/releases/download/v0.6.7/VoxCue-Setup-0.6.7-x64.exe) | Windows 10 / 11, 64-bit |
| macOS | [0.6.6 · Apple Silicon DMG](https://github.com/NCFXZ/VoxCue-releases/releases/download/v0.6.6/VoxCue-0.6.6-arm64.dmg) | macOS 14.2 or later, M-series chip |

Version 0.6.7 is a Windows release. Mac 0.6.7 is not yet available. Each platform checks for its own complete, stable release. For a first installation, download only the EXE or DMG; the app uses the other files for updates.

## Features

- **Interview preparation:** Add your résumé, job description, and attachments to discuss your experience, projects, and target role. The home screen offers three next steps based on your profile.
- **Generate and update skills:** Build interview knowledge and talking points from your résumé and job description. Review and save changes individually, keeping reference knowledge separate from your actual experience.
- **AI services:** Connect ChatGPT or GitHub Copilot independently in Settings. The model can search the web when needed. Preparation chats use selected knowledge bases only when explicitly requested.
- **Live interview assistance:** Transcribe system audio and microphone input separately. View questions and answers in an always-on-top window, or ask questions using text and screenshots.
- **Interview history:** Review transcripts, answers, and screenshots, with navigation, renaming, and export tools.
- **Profile and knowledge bases:** Manage personal information and source documents, use local retrieval when needed, and enable cloud backup separately for your profile, interview history, and knowledge bases.
- **Chinese and English UI:** Switch between Simplified Chinese and English, with light, dark, and system appearance. Chat and interview answers support LaTeX equations and matrices.

## What's new in 0.6.7

- Added complete Chinese and English UI. The first launch follows your system language; manual choices are remembered.
- Simplified home-screen guidance and improved hover descriptions, English layouts, and control alignment.
- Improved skill generation, updates, and individual review, with an option to prepare relevant skills after completing your profile.
- Let the model decide when to search the web. Preparation chats use knowledge bases only on explicit request.
- Added equation rendering in chat and interviews, with smoother skill-detail and reasoning-progress expansion, collapse, and scrolling.
- Fixed UI, stability, and security issues.

[Full release notes (中文 / English)](https://github.com/NCFXZ/VoxCue-releases/releases/tag/v0.6.7)

## Get started

1. Install and open VoxCue. Create or sign in to a VoxCue account, or skip sign-in to use local mode.
2. Connect ChatGPT or GitHub Copilot in **Settings → AI services**. Download the required speech and retrieval components under **Local components**.
3. Add your résumé and job description, review the AI's proposed changes, and generate interview skills when ready.
4. Check your audio devices before starting an interview, then use transcription, questions, and answers in the interview window.

VoxCue is free to use. Account eligibility and usage limits for AI services are determined by those services. Cloud backup requires a VoxCue account; local mode still supports independent AI-service connections. See the [user guide](https://voxcue.com.cn/install/) for detailed instructions.

## Installation and updates

On Windows, run the downloaded EXE. On Mac, open the DMG and drag VoxCue to Applications. Download speech and retrieval models from the app's settings as needed. Upgrades reuse previously downloaded components of the same version.

The `.blockmap`, `latest.yml`, `latest-mac.yml`, and Mac ZIP files are for automatic updates; they are not required for a first installation. If a verification email does not arrive, check your spam folder.

## Data and privacy

Speech recognition runs locally. Raw audio is neither saved nor uploaded. AI requests include the text and relevant excerpts needed for the task, plus attachments or screenshots you choose to submit. Cloud backup is enabled separately for your profile, interview history, and knowledge bases, with a default total capacity of 100 MB.

Basic usage statistics exclude chat and transcript content, source files, audio, screenshots, and access tokens. See the [user guide](https://voxcue.com.cn/install/) for feature details and instructions.
