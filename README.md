<!--
AUTO-GENERATED FILE.
Managed by .github/workflows/refresh-readme.yml
-->

<p align="center">
<img src="https://nuvio.tv/assets/nuvio-app-logo-wordmark.webp" alt="Nuvio" width="460">
</p>

<h2 align="center">
Nuvio iOS / iPadOS SideStore Distribution
</h2>

<p align="center">
Community-maintained SideStore source using the official Nuvio
FULL IPA whenever available, with an automatic source-build
fallback as a safety net.
</p>

<p align="center">
<img src="https://img.shields.io/badge/VERSION-0.4.15-2188ff?style=for-the-badge" alt="Version"> <img src="https://img.shields.io/badge/MINIMUM%20OS-iOS%20%2F%20iPadOS%2016.1%2B-555555?style=for-the-badge" alt="Minimum OS"> <img src="https://img.shields.io/badge/DEVICES-iPhone%20%26%20iPad-2ea44f?style=for-the-badge" alt="Devices"><br>
<img src="https://img.shields.io/badge/DISTRIBUTION-FULL-6f42c1?style=for-the-badge" alt="Distribution"> <img src="https://img.shields.io/badge/SIGNING-UNSIGNED%20IPA-e67e22?style=for-the-badge" alt="Signing"> <img src="https://img.shields.io/badge/UPDATES-AUTOMATIC-00a4ef?style=for-the-badge" alt="Updates"><br>
<img src="https://img.shields.io/badge/IPA%20SOURCE-OFFICIAL%20NUVIO-2ea44f?style=for-the-badge" alt="IPA source">
</p>

> [!IMPORTANT]
> **This is an unofficial SideStore distribution channel.**
>
> This repository is not affiliated with or endorsed by NuvioMedia.
> It prefers the official Nuvio FULL IPA and only compiles a fallback
> IPA from the matching official source when necessary.

<h2 align="center">📦 IPA Source</h2>

<p align="center">
<strong>OFFICIAL NUVIO</strong>
</p>

<p align="center">
This version uses the official Nuvio FULL IPA. The original IPA is downloaded from the matching NuvioMedia release, verified, and mirrored unchanged for SideStore distribution.
</p>

<h2 align="center">🚀 Latest Release</h2>

<p align="center">
<strong>Nuvio 0.4.15</strong><br>
Build 120 · iOS / iPadOS 16.1+ · iPhone & iPad<br>
FULL distribution · Unsigned IPA
</p>

<p align="center">
<a href="https://github.com/GrgoPitic/NuvioMobile/releases/tag/ios-0.4.15"><img src="https://img.shields.io/badge/GitHub_Release-VIEW_LATEST-2ea44f?style=for-the-badge&logo=github" alt="View latest release"></a> <a href="https://github.com/GrgoPitic/NuvioMobile/releases/download/ios-0.4.15/Nuvio-0.4.15.ipa"><img src="https://img.shields.io/badge/IPA-DOWNLOAD_LATEST-2188ff?style=for-the-badge&logo=apple" alt="Download IPA"></a>
</p>

<h2 align="center">🌍 Choose your language</h2>

<p align="center">
Open the complete guide in your preferred language.
</p>

<p align="center">
<a href="docs/readme/README_EN.md"><img src="https://img.shields.io/badge/ENGLISH-OPEN_GUIDE-2188ff?style=for-the-badge" alt="English"></a> <a href="docs/readme/README_SK.md"><img src="https://img.shields.io/badge/SLOVEN%C4%8CINA-OTVORI%C5%A4_N%C3%81VOD-2ea44f?style=for-the-badge" alt="Slovenčina"></a> <a href="docs/readme/README_CZ.md"><img src="https://img.shields.io/badge/%C4%8CE%C5%A0TINA-OTEV%C5%98%C3%8DT_N%C3%81VOD-e67e22?style=for-the-badge" alt="Čeština"></a>
</p>

<p align="center">
🇬🇧 English &nbsp;&nbsp; • &nbsp;&nbsp;
🇸🇰 Slovenčina &nbsp;&nbsp; • &nbsp;&nbsp;
🇨🇿 Čeština
</p>

<h2 align="center">🔗 SideStore Automatic Updates</h2>

<p align="center">
Add this source once and future versions can appear
automatically in SideStore.
</p>

```text
https://raw.githubusercontent.com/GrgoPitic/NuvioMobile/cmp-rewrite/sidestore/source.json
```

<p align="center">
<a href="https://raw.githubusercontent.com/GrgoPitic/NuvioMobile/cmp-rewrite/sidestore/source.json"><img src="https://img.shields.io/badge/SideStore-source.json-6f42c1?style=for-the-badge&logo=apple" alt="SideStore source"></a>
</p>

<p align="center">
<strong>SideStore → Sources → Add Source</strong>
</p>

<h2 align="center">✨ What's New in 0.4.15</h2>

- cf6cf2d6 fix(auth): synchronize shared client initialization @tapframe  
- 28df1e7d fix(home): restore hero position when switching profiles @tapframe  
- 972109f9 fix(playback): disable play when no source is available @tapframe  
- 872a5937 fix(home): reduce hero height without continue watching @tapframe  
- [Fix NetworkOnMainThreadException when starting a download (#1893)](https://github.com/NuvioMedia/NuvioMobile/pull/1893) @Axl-Lvy  
- 526a5b97 feat: custom static colours @tapframe  
- 68337ffa feat(members): custom gradient @tapframe  
- [Added Russian translation (#1886)](https://github.com/NuvioMedia/NuvioMobile/pull/1886) @zamalatb  
- 378f120e fix(downloads): exclude foreground service from playstore builds @tapframe  
- 6d4ad8bb fix(player): preserve each foreground service start notification @tapframe  
- 40af63ad fix(player): synchronize native subtitle rendering @tapframe  
- 3554904b fix(player): resolve subtitle formats off the main thread @tapframe  
- 42667b9f feat(ui): unify skeleton loading states @tapframe  
- 5fa890ee perf(home): improve lazy list item reuse @tapframe  
- 8b43fd89 perf(startup): avoid redundant collection and catalog processing @tapframe  
- e306a0a0 perf(ios): release temporary GIF decoding resources @tapframe  
- 59a13cbf perf(loading): cache bundled animation resource reads @tapframe  
- 6fb5d44f perf(ui): defer loading and parallax state reads @tapframe  
- d7159342 fix(streams): refresh resume position Fixes #1866 @tapframe  
- 3c239664 fix(android): background downloads @tapframe

---

<h2 align="center">🔎 Verification</h2>

<details>
<summary><strong>Show technical information</strong></summary>

```text
Official repository: NuvioMedia/NuvioMobile
Official tag:        0.4.15
Version:             0.4.15
Build:               120
Minimum OS:          iOS / iPadOS 16.1+
Supported devices:   iPhone & iPad
Distribution:        FULL
Signing:             Unsigned IPA
IPA source:          Official Nuvio IPA
Source reference:    Official release asset
IPA SHA256:          aebc751424db7b08d800188f311b88b98ff82d081637273c90b3ce339560aa2b
```

</details>

---

<h2 align="center">❤️ Official Nuvio Project</h2>

<p align="center">
Original Nuvio project, source code and official releases:<br><br>

<strong>
<a href="https://github.com/NuvioMedia/NuvioMobile">
NuvioMedia/NuvioMobile
</a>
</strong><br><br>

Source version corresponding to this release:
<a href="https://github.com/NuvioMedia/NuvioMobile/tree/0.4.15">0.4.15</a>
</p>

<p align="center">
💜 Thank you for supporting Nuvio and the community.
</p>
