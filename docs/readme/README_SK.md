<p align="center">
  <img
    src="https://nuvio.tv/assets/nuvio-app-logo-wordmark.webp"
    alt="Nuvio"
    width="500"
  />
</p>


# 🇸🇰 Nuvio pre iOS / iPadOS — Slovenský návod

[← Späť na hlavnú stránku](../../README.md)

> [!IMPORTANT]
> Toto je **neoficiálny komunitný build Nuvio**.
> Nejde o oficiálnu distribúciu spoločnosti NuvioMedia.

## Aktuálna verzia

| Informácia | Hodnota |
| --- | --- |
| Verzia | **0.4.11** |
| Build | **115** |
| Minimálny systém | **iOS / iPadOS 16.1+** |
| Podporované zariadenia | **iPhone & iPad** |
| Distribúcia | **FULL** |
| Podpis | **Nepodpísaná IPA** |

## Automatické aktualizácie cez SideStore

V SideStore otvor:

**Sources → Add Source**

a pridaj:

```text
https://raw.githubusercontent.com/GrgoPitic/NuvioMobile/cmp-rewrite/sidestore/source.json
```

Po pridaní zdroja sa nové verzie môžu zobrazovať
automaticky po úspešnom zostavení nového
oficiálneho vydania Nuvio.

## Stiahnuť najnovšiu IPA

**[Stiahnuť Nuvio 0.4.11 IPA](https://github.com/GrgoPitic/NuvioMobile/releases/download/ios-0.4.11/Nuvio-0.4.11.ipa)**

## Čo je nové vo verzii 0.4.11

## What's Changed

- 04ca1226 feat(details): add tappable expandable descriptions @tapframe
- [fix: Simkl anime type classification and landscape poster aspect ratio (#1786)](https://github.com/NuvioMedia/NuvioMobile/pull/1786) @skoruppa
- aa67e069 fix(details): reset episode position when switching seasons @tapframe
- ab57cf1b fix(search): persist discover catalog selection @tapframe
- 560e5a28 fix(ios): correct launch screen configuration @tapframe
- 2c7438d6 fix(player): make subtitle aggregation multiplatform @tapframe
- [Respect corner radius for trailers and episodes (#1784)](https://github.com/NuvioMedia/NuvioMobile/pull/1784) @skoruppa
- [i18n(el): add missing Greek translations (#1783)](https://github.com/NuvioMedia/NuvioMobile/pull/1783) @nosvasedis
- 96fb98c4 fix(catalog): preserve scroll position after details @tapframe
- 191be42a fix: address mobile crash clusters (NUVIO-MOBILE-4 NUVIO-MOBILE-QK NUVIO-MOBILE-FZ) @tapframe
- [Latest strings added to the Bulgarian translation (#1779)](https://github.com/NuvioMedia/NuvioMobile/pull/1779) @viiktr
- [fix: per-episode rating from addon metadata is never parsed (#1776)](https://github.com/NuvioMedia/NuvioMobile/pull/1776) @6ip
- [feat(player): port sidecar addon subtitles, fix selection state, and parallelize fetching (#1705)](https://github.com/NuvioMedia/NuvioMobile/pull/1705) @halibiram

## O tomto builde

- Zdrojový kód aplikácie neupravujeme.
- Build vzniká z oficiálnej verzie Nuvio **0.4.11**.
- Používa sa distribúcia FULL.
- IPA nie je podpísaná a je určená pre SideStore.
- Projekt je komunitne udržiavaný.
- Nejde o oficiálnu distribúciu NuvioMedia.

## Overenie buildu

```text
Oficiálny tag:     0.4.11
Oficiálny commit:  1c92795c2c54631a32ed973cf989bdcedfd52271
IPA SHA256:        c3934bfcc1e4914a847d64b5e1cfc7a4c8c8db51d4986ef11cf5dff6651f2aed
```

[← Späť na hlavnú stránku](../../README.md)
