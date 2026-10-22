# Saifer Browser

<div align="center">
  <img src="assets/saifer-logo.png" alt="Saifer Browser — blue fox and globe emblem" width="180" />
  <h3>Private by design. Fast by nature.</h3>
  <p>A modern Android browser project based on Via Browser.</p>
</div>

Saifer Browser is a brand-customized Android browser built on the lightweight Via Browser WebView codebase. The goal is a polished, privacy-forward experience with modern media and reading tools.

## Current foundation
The upstream Via project already includes browser basics such as tabs, bookmarks, downloads, ad blocking, reader mode, page translation, resource sniffing, picture-in-picture, and customization. Actual behavior depends on Android System WebView and device capabilities.

## Saifer roadmap inspired by Quetta
- **Brand identity:** Saifer name, original blue fox/globe logo, and a premium visual system.
- **Media:** media detection/downloads, dedicated playback, playlists, background audio, picture-in-picture and playback speed where supported.
- **Privacy:** clearer tracking/ad blocking controls, third-party cookie controls, HTTPS preference and Global Privacy Control where available.
- **Reading & productivity:** reader mode, webpage capture, PDF export and translation workflows.
- **Private storage:** an app-lock/biometric-protected local vault for selected data.
- **Extensions:** research a feasible Android extension runtime; standard WebView alone does not provide Chrome/Edge extension compatibility.
- **Quality:** accessibility, security checks, device testing and repeatable release builds.

**Important:** this list is a development roadmap, not a claim that every Quetta feature is implemented today. Each feature must be wired into the Android application and tested; no proprietary Quetta code or assets are included.

## Build
Open the upstream Android project in Android Studio and use its Gradle configuration. An APK should only be described as release-ready after successful CI compilation and device checks.

## Attribution
Saifer is based on the Via Browser project by [tuyafeng](https://github.com/tuyafeng/Via). Consult upstream license and notices before distributing builds.
