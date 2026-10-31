<p align="center">
<img src="https://nuvio.tv/assets/nuvio-app-logo-wordmark.webp" alt="Nuvio" width="460">
</p>

<h1 align="center">
🇸🇰 Nuvio pre iOS / iPadOS — Slovenský návod
</h1>

<p align="center">
<a href="../../README.md">← Späť na hlavnú stránku</a>
</p>

<p align="center">
<img src="https://img.shields.io/badge/VERSION-0.6.6-2188ff?style=for-the-badge" alt="Version"> <img src="https://img.shields.io/badge/MINIMUM%20OS-iOS%20%2F%20iPadOS%2016.1%2B-555555?style=for-the-badge" alt="Minimum OS"> <img src="https://img.shields.io/badge/DEVICES-iPhone%20%26%20iPad-2ea44f?style=for-the-badge" alt="Devices"><br>
<img src="https://img.shields.io/badge/DISTRIBUTION-FULL-6f42c1?style=for-the-badge" alt="Distribution"> <img src="https://img.shields.io/badge/SIGNING-UNSIGNED%20IPA-e67e22?style=for-the-badge" alt="Signing"> <img src="https://img.shields.io/badge/UPDATES-AUTOMATIC-00a4ef?style=for-the-badge" alt="Updates"><br>
<img src="https://img.shields.io/badge/IPA%20SOURCE-OFFICIAL%20NUVIO-2ea44f?style=for-the-badge" alt="IPA source">
</p>

> [!IMPORTANT]
> Toto je **neoficiálny komunitný distribučný kanál pre SideStore**.
> Nejde o oficiálny distribučný kanál spoločnosti NuvioMedia.

<h2 align="center">📦 Pôvod IPA</h2>

<p align="center">
<strong>OFFICIAL NUVIO</strong><br><br>
Táto verzia používa oficiálnu FULL IPA aplikácie Nuvio. Originálna IPA sa stiahne z príslušného vydania NuvioMedia, overí sa a bez zmeny sa zrkadlí pre distribúciu cez SideStore.
</p>

<h2 align="center">📱 Aktuálna verzia</h2>

<p align="center">
<strong>Nuvio 0.6.6</strong><br>
Build 149<br>
iOS / iPadOS 16.1+<br>
iPhone & iPad<br>
FULL · Nepodpísaná IPA
</p>

<p align="center">
<a href="https://github.com/GrgoPitic/NuvioMobile/releases/tag/ios-0.6.6-beta"><img src="https://img.shields.io/badge/GitHub_Release-VIEW_LATEST-2ea44f?style=for-the-badge&logo=github" alt="View latest release"></a> <a href="https://github.com/GrgoPitic/NuvioMobile/releases/download/ios-0.6.6-beta/Nuvio-0.6.6.ipa"><img src="https://img.shields.io/badge/IPA-DOWNLOAD_LATEST-2188ff?style=for-the-badge&logo=apple" alt="Download IPA"></a>
</p>

<h2 align="center">🔗 Automatické aktualizácie cez SideStore</h2>

<p align="center">
V SideStore otvor <strong>Sources → Add Source</strong>
a vlož:
</p>

```text
https://raw.githubusercontent.com/GrgoPitic/NuvioMobile/cmp-rewrite/sidestore/source.json
```

<p align="center">
<a href="https://raw.githubusercontent.com/GrgoPitic/NuvioMobile/cmp-rewrite/sidestore/source.json"><img src="https://img.shields.io/badge/SideStore-source.json-6f42c1?style=for-the-badge&logo=apple" alt="SideStore source"></a>
</p>

<h2 align="center">✨ Čo je nové vo verzii 0.6.6</h2>

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

<h2 align="center">ℹ️ Ako distribúcia funguje</h2>

- Vždy sa preferuje oficiálna FULL IPA.
- Oficiálna IPA sa pred publikovaním overí.
- Dáta oficiálnej IPA sa pri zrkadlení nemenia.
- Ak oficiálna IPA nie je použiteľná, aktivuje sa záložný build.
- Záložný build používa presný zodpovedajúci oficiálny zdroj Nuvio.
- SideStore URL zostáva v oboch prípadoch rovnaká.

<h2 align="center">🔎 Overenie</h2>

<details>
<summary><strong>Zobraziť technické údaje</strong></summary>

```text
Oficiálny tag:     0.6.6-beta
IPA source:        Official Nuvio IPA
Source reference:  Official release asset
IPA SHA256:        6250d33e6231608a409b5173f2e92496aec5198919967ca60c9af3f488b24453
```

</details>

<p align="center">
<a href="../../README.md">← Späť na hlavnú stránku</a>
</p>
