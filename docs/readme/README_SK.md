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
<img src="https://img.shields.io/badge/VERSION-0.4.15-2188ff?style=for-the-badge" alt="Version"> <img src="https://img.shields.io/badge/MINIMUM%20OS-iOS%20%2F%20iPadOS%2016.1%2B-555555?style=for-the-badge" alt="Minimum OS"> <img src="https://img.shields.io/badge/DEVICES-iPhone%20%26%20iPad-2ea44f?style=for-the-badge" alt="Devices"><br>
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
<strong>Nuvio 0.4.15</strong><br>
Build 120<br>
iOS / iPadOS 16.1+<br>
iPhone & iPad<br>
FULL · Nepodpísaná IPA
</p>

<p align="center">
<a href="https://github.com/GrgoPitic/NuvioMobile/releases/tag/ios-0.4.15"><img src="https://img.shields.io/badge/GitHub_Release-VIEW_LATEST-2ea44f?style=for-the-badge&logo=github" alt="View latest release"></a> <a href="https://github.com/GrgoPitic/NuvioMobile/releases/download/ios-0.4.15/Nuvio-0.4.15.ipa"><img src="https://img.shields.io/badge/IPA-DOWNLOAD_LATEST-2188ff?style=for-the-badge&logo=apple" alt="Download IPA"></a>
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

<h2 align="center">✨ Čo je nové vo verzii 0.4.15</h2>

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
Oficiálny tag:     0.4.15
IPA source:        Official Nuvio IPA
Source reference:  Official release asset
IPA SHA256:        aebc751424db7b08d800188f311b88b98ff82d081637273c90b3ce339560aa2b
```

</details>

<p align="center">
<a href="../../README.md">← Späť na hlavnú stránku</a>
</p>
