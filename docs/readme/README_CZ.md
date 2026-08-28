<p align="center">
  <img
    src="https://nuvio.tv/assets/nuvio-app-logo-wordmark.webp"
    alt="Nuvio"
    width="500"
  />
</p>


# 🇨🇿 Nuvio pro iOS / iPadOS — Český návod

[← Zpět na hlavní stránku](../../README.md)

> [!IMPORTANT]
> Toto je **neoficiální komunitní build Nuvio**.
> Nejde o oficiální distribuci společnosti NuvioMedia.

## Aktuální verze

| Informace | Hodnota |
| --- | --- |
| Verze | **0.4.11** |
| Build | **115** |
| Minimální systém | **iOS / iPadOS 16.1+** |
| Podporovaná zařízení | **iPhone & iPad** |
| Distribuce | **FULL** |
| Podpis | **Nepodepsaná IPA** |

## Automatické aktualizace přes SideStore

V SideStore otevři:

**Sources → Add Source**

a přidej:

```text
https://raw.githubusercontent.com/GrgoPitic/NuvioMobile/cmp-rewrite/sidestore/source.json
```

Po přidání zdroje se nové verze mohou zobrazovat
automaticky po úspěšném sestavení nového
oficiálního vydání Nuvio.

## Stáhnout nejnovější IPA

**[Stáhnout Nuvio 0.4.11 IPA](https://github.com/GrgoPitic/NuvioMobile/releases/download/ios-0.4.11/Nuvio-0.4.11.ipa)**

## Co je nového ve verzi 0.4.11

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

## O tomto buildu

- Zdrojový kód aplikace neupravujeme.
- Build vzniká z oficiální verze Nuvio **0.4.11**.
- Používá se distribuce FULL.
- IPA není podepsaná a je určena pro SideStore.
- Projekt je komunitně udržovaný.
- Nejde o oficiální distribuci NuvioMedia.

## Ověření buildu

```text
Oficiální tag:     0.4.11
Oficiální commit:  1c92795c2c54631a32ed973cf989bdcedfd52271
IPA SHA256:        c3934bfcc1e4914a847d64b5e1cfc7a4c8c8db51d4986ef11cf5dff6651f2aed
```

[← Zpět na hlavní stránku](../../README.md)
