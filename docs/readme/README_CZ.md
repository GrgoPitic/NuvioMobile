<p align="center">
<img src="https://nuvio.tv/assets/nuvio-app-logo-wordmark.webp" alt="Nuvio" width="460">
</p>

<h1 align="center">
🇨🇿 Nuvio pro iOS / iPadOS — Český návod
</h1>

<p align="center">
<a href="../../README.md">← Zpět na hlavní stránku</a>
</p>

<p align="center">
<img src="https://img.shields.io/badge/VERSION-0.6.4-2188ff?style=for-the-badge" alt="Version"> <img src="https://img.shields.io/badge/MINIMUM%20OS-iOS%20%2F%20iPadOS%2016.1%2B-555555?style=for-the-badge" alt="Minimum OS"> <img src="https://img.shields.io/badge/DEVICES-iPhone%20%26%20iPad-2ea44f?style=for-the-badge" alt="Devices"><br>
<img src="https://img.shields.io/badge/DISTRIBUTION-FULL-6f42c1?style=for-the-badge" alt="Distribution"> <img src="https://img.shields.io/badge/SIGNING-UNSIGNED%20IPA-e67e22?style=for-the-badge" alt="Signing"> <img src="https://img.shields.io/badge/UPDATES-AUTOMATIC-00a4ef?style=for-the-badge" alt="Updates"><br>
<img src="https://img.shields.io/badge/IPA%20SOURCE-OFFICIAL%20NUVIO-2ea44f?style=for-the-badge" alt="IPA source">
</p>

> [!IMPORTANT]
> Toto je **neoficiální komunitní distribuční kanál pro SideStore**.
> Nejde o oficiální distribuční kanál společnosti NuvioMedia.

<h2 align="center">📦 Původ IPA</h2>

<p align="center">
<strong>OFFICIAL NUVIO</strong><br><br>
Tato verze používá oficiální FULL IPA aplikace Nuvio. Originální IPA se stáhne z příslušného vydání NuvioMedia, ověří se a beze změny se zrcadlí pro distribuci přes SideStore.
</p>

<h2 align="center">📱 Aktuální verze</h2>

<p align="center">
<strong>Nuvio 0.6.4</strong><br>
Build 147<br>
iOS / iPadOS 16.1+<br>
iPhone & iPad<br>
FULL · Nepodepsaná IPA
</p>

<p align="center">
<a href="https://github.com/GrgoPitic/NuvioMobile/releases/tag/ios-0.6.4-beta"><img src="https://img.shields.io/badge/GitHub_Release-VIEW_LATEST-2ea44f?style=for-the-badge&logo=github" alt="View latest release"></a> <a href="https://github.com/GrgoPitic/NuvioMobile/releases/download/ios-0.6.4-beta/Nuvio-0.6.4.ipa"><img src="https://img.shields.io/badge/IPA-DOWNLOAD_LATEST-2188ff?style=for-the-badge&logo=apple" alt="Download IPA"></a>
</p>

<h2 align="center">🔗 Automatické aktualizace přes SideStore</h2>

<p align="center">
V SideStore otevři <strong>Sources → Add Source</strong>
a vlož:
</p>

```text
https://raw.githubusercontent.com/GrgoPitic/NuvioMobile/cmp-rewrite/sidestore/source.json
```

<p align="center">
<a href="https://raw.githubusercontent.com/GrgoPitic/NuvioMobile/cmp-rewrite/sidestore/source.json"><img src="https://img.shields.io/badge/SideStore-source.json-6f42c1?style=for-the-badge&logo=apple" alt="SideStore source"></a>
</p>

<h2 align="center">✨ Co je nového ve verzi 0.6.4</h2>

- 8683505d fix(details): animate ratings on tablet @tapframe  
- e6a05d1d feat(ios): support duo layout @tapframe  
- b6287380 fix(deps): update haze to 1.7.3 @tapframe  
- [fix(trakt): keep continue watching when a progress request fails (#2366)](https://github.com/NuvioMedia/NuvioMobile/pull/2366) @kernexshadow  
- [perf(streams): compile badge rules once per change (#2365)](https://github.com/NuvioMedia/NuvioMobile/pull/2365) @kernexshadow  
- [perf(debrid): cache stream filter regexes and reuse stream facts (#2362)](https://github.com/NuvioMedia/NuvioMobile/pull/2362) @kernexshadow  
- [i18n(el): sync the Greek locale with 0.6.3 (player badges, Simkl statuses, engine switch, party chat) (#2359)](https://github.com/NuvioMedia/NuvioMobile/pull/2359) @nosvasedis  
- [feat(i18n): complete pt-BR player badges and watch party strings (#2338)](https://github.com/NuvioMedia/NuvioMobile/pull/2338) @jhojhocraazy  
- [Replace libass renderer with atlas pipeline from Plezy (#2346)](https://github.com/NuvioMedia/NuvioMobile/pull/2346) @skoruppa  
- [Update Hungarian translations (#2341)](https://github.com/NuvioMedia/NuvioMobile/pull/2341) @emgeje  
- [i18n(vi): update strings.xml and strings_party.xml (#2339)](https://github.com/NuvioMedia/NuvioMobile/pull/2339) @blueocean2308  
- 90ab7f95 fix(ratings): use real imdb logo and grey label @tapframe  
- d9046775 feat(home): show ratings and age rating on hero @tapframe  
- b9fbc09c fix(player): keep side panels clear of the navigation bar @tapframe  
- 83e528f0 feat(player): choose a badge pack for the player @tapframe  
- [Complete Spanish mobile translations (#2344)](https://github.com/NuvioMedia/NuvioMobile/pull/2344) @IberianSoldierPC  
- [fix(ios): keep hardware decoding when PiP is interrupted by Notification Center (#2306)](https://github.com/NuvioMedia/NuvioMobile/pull/2306) @WhiteGiso  
- [fix(android): scale ExoPlayer subtitles with the PiP window size (#2314)](https://github.com/NuvioMedia/NuvioMobile/pull/2314) @sap6  
- [feat(player): auto-sync add-on subtitles on the libmpv engine (#2275)](https://github.com/NuvioMedia/NuvioMobile/pull/2275) @kernexshadow

<h2 align="center">ℹ️ Jak distribuce funguje</h2>

- Vždy se preferuje oficiální FULL IPA.
- Oficiální IPA se před publikováním ověří.
- Data oficiální IPA se při zrcadlení nemění.
- Pokud oficiální IPA není použitelná, aktivuje se záložní build.
- Záložní build používá přesný odpovídající oficiální zdroj Nuvio.
- SideStore URL zůstává v obou případech stejná.

<h2 align="center">🔎 Ověření</h2>

<details>
<summary><strong>Zobrazit technické údaje</strong></summary>

```text
Oficiální tag:     0.6.4-beta
IPA source:        Official Nuvio IPA
Source reference:  Official release asset
IPA SHA256:        e7670fdba3adb96f6f8292dd19539fff04d1fbd792fa0fc7b1f602b84367d969
```

</details>

<p align="center">
<a href="../../README.md">← Zpět na hlavní stránku</a>
</p>
