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
<img src="https://img.shields.io/badge/VERSION-0.6.6-2188ff?style=for-the-badge" alt="Version"> <img src="https://img.shields.io/badge/MINIMUM%20OS-iOS%20%2F%20iPadOS%2016.1%2B-555555?style=for-the-badge" alt="Minimum OS"> <img src="https://img.shields.io/badge/DEVICES-iPhone%20%26%20iPad-2ea44f?style=for-the-badge" alt="Devices"><br>
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
<strong>Nuvio 0.6.6</strong><br>
Build 149 · iOS / iPadOS 16.1+ · iPhone & iPad<br>
FULL distribution · Unsigned IPA
</p>

<p align="center">
<a href="https://github.com/GrgoPitic/NuvioMobile/releases/tag/ios-0.6.6-beta"><img src="https://img.shields.io/badge/GitHub_Release-VIEW_LATEST-2ea44f?style=for-the-badge&logo=github" alt="View latest release"></a> <a href="https://github.com/GrgoPitic/NuvioMobile/releases/download/ios-0.6.6-beta/Nuvio-0.6.6.ipa"><img src="https://img.shields.io/badge/IPA-DOWNLOAD_LATEST-2188ff?style=for-the-badge&logo=apple" alt="Download IPA"></a>
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

<h2 align="center">✨ What's New in 0.6.6</h2>

- [Translation improvements and adjustments for Slovak language + added translated new strings files (#2448)](https://github.com/NuvioMedia/NuvioMobile/pull/2448) @mmsw91
- [improve player badge codec detection and add filename matching (#2414)](https://github.com/NuvioMedia/NuvioMobile/pull/2414) @skoruppa
- [Add intro, outro and recap skipping from MKV chapter titles (#2446)](https://github.com/NuvioMedia/NuvioMobile/pull/2446) @skoruppa 
- [feat(i18n): translate settings groups, subtitle appearance and ASS render modes (#2435)](https://github.com/NuvioMedia/NuvioMobile/pull/2435) @jhojhocraazy
- Update Vietnamese translations ([#2441](https://github.com/NuvioMedia/NuvioMobile/pull/2441), [#2411](https://github.com/NuvioMedia/NuvioMobile/pull/2411)) @blueocean2308
- Add subtitle customization with saved styles, custom font imports, appearance controls and a live preview, including fixes for font rendering, subtitle loading, track changes and style updates while paused. @tapframe
- [Updated Bulgarian translations (#2424)](https://github.com/NuvioMedia/NuvioMobile/pull/2424) @viiktr
- [fix(ios): resume PiP right after Notification Center (#2418)](https://github.com/NuvioMedia/NuvioMobile/pull/2418) @WhiteGiso
- c7ff35f0 feat(settings): group settings and split playback pages @tapframe
- 96061025 fix(ratings): show IMDb ratings with one decimal @tapframe
- 2f0185ce feat(details): label unreleased episodes as unavailable @tapframe
- 87795e97 fix(settings): save and restore the selected app icon @tapframe
- [Draw ASS subtitles onto video frames via setVideoEffects + ASS Render Mode setting (#2394)](https://github.com/NuvioMedia/NuvioMobile/pull/2394) @skoruppa
- 45af99c4 fix(player): skip drag handling while controls are locked @tapframe
- [fix(player): offline playback performance and reliability (#2383)](https://github.com/NuvioMedia/NuvioMobile/pull/2383) @guuilp
- [feat(player): Auto engine selection and engine failover (#2192)](https://github.com/NuvioMedia/NuvioMobile/pull/2192) @guuilp

---

<h2 align="center">🔎 Verification</h2>

<details>
<summary><strong>Show technical information</strong></summary>

```text
Official repository: NuvioMedia/NuvioMobile
Official tag:        0.6.6-beta
Version:             0.6.6
Build:               149
Minimum OS:          iOS / iPadOS 16.1+
Supported devices:   iPhone & iPad
Distribution:        FULL
Signing:             Unsigned IPA
IPA source:          Official Nuvio IPA
Source reference:    Official release asset
IPA SHA256:          6250d33e6231608a409b5173f2e92496aec5198919967ca60c9af3f488b24453
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
<a href="https://github.com/NuvioMedia/NuvioMobile/tree/0.6.6-beta">0.6.6-beta</a>
</p>

<p align="center">
💜 Thank you for supporting Nuvio and the community.
</p>
