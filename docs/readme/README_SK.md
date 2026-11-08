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
<img src="https://img.shields.io/badge/VERSION-0.6.10-2188ff?style=for-the-badge" alt="Version"> <img src="https://img.shields.io/badge/MINIMUM%20OS-iOS%20%2F%20iPadOS%2016.1%2B-555555?style=for-the-badge" alt="Minimum OS"> <img src="https://img.shields.io/badge/DEVICES-iPhone%20%26%20iPad-2ea44f?style=for-the-badge" alt="Devices"><br>
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
<strong>Nuvio 0.6.10</strong><br>
Build 153<br>
iOS / iPadOS 16.1+<br>
iPhone & iPad<br>
FULL · Nepodpísaná IPA
</p>

<p align="center">
<a href="https://github.com/GrgoPitic/NuvioMobile/releases/tag/ios-0.6.10-beta"><img src="https://img.shields.io/badge/GitHub_Release-VIEW_LATEST-2ea44f?style=for-the-badge&logo=github" alt="View latest release"></a> <a href="https://github.com/GrgoPitic/NuvioMobile/releases/download/ios-0.6.10-beta/Nuvio-0.6.10.ipa"><img src="https://img.shields.io/badge/IPA-DOWNLOAD_LATEST-2188ff?style=for-the-badge&logo=apple" alt="Download IPA"></a>
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

<h2 align="center">✨ Čo je nové vo verzii 0.6.10</h2>

- c1dfd989 fix(player): start playback service as a normal service first (NUVIO-MOBILE-D9 NUVIO-MOBILE-9E NUVIO-MOBILE-9M NUVIO-MOBILE-PC) @tapframe  
- 6ad2d9ba fix(player): cap buffer start times at the min buffer (NUVIO-MOBILE-1VH) @tapframe  
- 81dc761e fix(player): guard caption setting reads (NUVIO-MOBILE-25M) @tapframe  
- d534d14e fix(network): treat SSL setup errors as failed requests (NUVIO-MOBILE-254 NUVIO-MOBILE-3N) @tapframe  
- 8172e682 fix(watched): copy unsynced keys before saving (NUVIO-MOBILE-260) @tapframe  
- [i18n: add French translation for ratings strings (#2562)](https://github.com/NuvioMedia/NuvioMobile/pull/2562) @SK-Gits  
- [i18n(el): sync the Greek locale with 0.6.9 (playback audio, downmix, ratings) (#2561)](https://github.com/NuvioMedia/NuvioMobile/pull/2561) @nosvasedis  
- [i18n(he): translate party strings into Hebrew (#2557)](https://github.com/NuvioMedia/NuvioMobile/pull/2557) @haveAnIssue  
- [i18n(he): translate servers strings into Hebrew (#2556)](https://github.com/NuvioMedia/NuvioMobile/pull/2556) @haveAnIssue  
- [i18n(he): translate pip strings into Hebrew (#2555)](https://github.com/NuvioMedia/NuvioMobile/pull/2555) @haveAnIssue  
- [i18n(he): translate autosync strings into Hebrew (#2553)](https://github.com/NuvioMedia/NuvioMobile/pull/2553) @haveAnIssue  
- [i18n(he): translate mdblist strings into Hebrew (#2552)](https://github.com/NuvioMedia/NuvioMobile/pull/2552) @haveAnIssue  
- [i18n(he): translate ratings strings into Hebrew (#2551)](https://github.com/NuvioMedia/NuvioMobile/pull/2551) @haveAnIssue  
- [Update Japanese translation (#2559)](https://github.com/NuvioMedia/NuvioMobile/pull/2559) @Joe00011  
- [i18n(vi): translate ratings strings into Vietnamese (#2550)](https://github.com/NuvioMedia/NuvioMobile/pull/2550) @blueocean2308  
- 82ca7d11 fix(player): reset addon subtitles only when the source changes @tapframe  
- [feat(autosync): shared engine, enable on iOS (#2535)](https://github.com/NuvioMedia/NuvioMobile/pull/2535) @skoruppa  
- [fix(mdblist): remap anime episodes between addon and TMDB numbering (TV parity) (#2516)](https://github.com/NuvioMedia/NuvioMobile/pull/2516) @kernexshadow

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
Oficiálny tag:     0.6.10-beta
IPA source:        Official Nuvio IPA
Source reference:  Official release asset
IPA SHA256:        a6fcd55733485bd24bd38669abaab65c2fc102d866d083d8a4bdf4797fa91935
```

</details>

<p align="center">
<a href="../../README.md">← Späť na hlavnú stránku</a>
</p>
