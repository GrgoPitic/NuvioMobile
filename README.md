<div align="center">

  <img src="https://nuvio.tv/assets/nuvio-app-logo-wordmark.webp" alt="Nuvio" width="320" />

  <p>
    A free, open-source media app for your phone, your desktop, and the TV you already own.
    <br />
    Bring your own sources. Nuvio turns them into a library with artwork, ratings, subtitles, and your place saved on every screen.
  </p>

  [Website](https://nuvio.tv) · [GitHub releases](https://github.com/NuvioMedia/NuvioMobile/releases/latest) · [Support Nuvio](https://nuvio.tv/support)

</div>

## Get Nuvio Mobile

- [Android on Google Play](https://play.google.com/store/apps/details?id=com.nuvio.app)
- [Android APK](https://github.com/NuvioMedia/NuvioMobile/releases/latest)
- iOS must be built from source.

## Build from source

```bash
git clone https://github.com/NuvioMedia/NuvioMobile.git
cd NuvioMobile
```

### Android

Android development requires Android Studio and the Android SDK.

```bash
./gradlew :androidApp:assembleFullDebug
```

### iOS

iOS development requires macOS and Xcode.

```bash
env NUVIO_IOS_DISTRIBUTION=full xcodebuild \
  -project iosApp/iosApp.xcodeproj \
  -scheme iosApp \
  -configuration Debug \
  -sdk iphonesimulator \
  -derivedDataPath build/ios-derived-full-simulator \
  CODE_SIGNING_ALLOWED=NO \
  build
```

The shared app is built with Kotlin Multiplatform and Compose Multiplatform.

## License

[GNU General Public License v3.0](./LICENSE)

<p align="center">
  <strong>🎬 Unofficial clean IPA build · Community-maintained iOS package</strong>
</p>

> [!NOTE]
> This repository provides **unofficial unsigned iOS / iPadOS builds**
> and SideStore distribution for Nuvio.
> The application source code is built from the corresponding
> official `NuvioMedia/NuvioMobile` release.

### Current SideStore build

| | |
| --- | --- |
| **Latest version** | **0.4.11** |
| **Minimum OS** | **iOS / iPadOS 16.1+** |
| **Supported devices** | **iPhone & iPad** |
| **Distribution** | **FULL** |
| **Signing** | **Unsigned IPA** |
| **Official source** | [`0.4.11`](https://github.com/NuvioMedia/NuvioMobile/tree/0.4.11) |
| **IPA SHA256** | `c3934bfcc1e4914a847d64b5e1cfc7a4c8c8db51d4986ef11cf5dff6651f2aed` |
| **Release** | [Nuvio iOS 0.4.11](https://github.com/GrgoPitic/NuvioMobile/releases/tag/ios-0.4.11) |

<table>
  <tr>
    <td width="33%">
      🇬🇧 <strong>English</strong><br><br>
      Instructions and information for English-speaking users.<br><br>
      <a href="#english">Go to English section →</a>
    </td>
    <td width="33%">
      🇨🇿 <strong>Čeština</strong><br><br>
      Pokyny a informace pro uživatele z Česka.<br><br>
      <a href="#čeština">Přejít na českou sekci →</a>
    </td>
    <td width="33%">
      🇸🇰 <strong>Slovenčina</strong><br><br>
      Pokyny a informácie pre používateľov zo Slovenska.<br><br>
      <a href="#slovenčina">Prejsť na slovenskú sekciu →</a>
    </td>
  </tr>
</table>

## 🔗 SideStore Update (`source.json`)

Add the following source to SideStore to receive automatic updates:

```text
https://raw.githubusercontent.com/GrgoPitic/NuvioMobile/cmp-rewrite/sidestore/source.json
```

**SideStore → Sources → Add Source → paste the URL above**

## ✨ What's new in 0.4.11

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

<details>
<summary><strong>🇬🇧 English</strong></summary>

### English

This is an **unofficial clean unsigned IPA build** of Nuvio
for iOS / iPadOS.

- Current version: **0.4.11**
- Minimum system: **iOS / iPadOS 16.1+**
- Supported devices: **iPhone & iPad**
- Distribution: **FULL**
- Signing: **Unsigned IPA**

Add this URL in **SideStore → Sources → Add Source**:

```text
https://raw.githubusercontent.com/GrgoPitic/NuvioMobile/cmp-rewrite/sidestore/source.json
```

This project is community-maintained and is not an official
NuvioMedia distribution.

</details>

<details>
<summary><strong>🇨🇿 Čeština</strong></summary>

### Čeština

Toto je **neoficiální čistý nepodepsaný IPA build** Nuvio
pro iOS / iPadOS.

- Aktuální verze: **0.4.11**
- Minimální systém: **iOS / iPadOS 16.1+**
- Podporovaná zařízení: **iPhone & iPad**
- Distribuce: **FULL**
- Podpis: **Unsigned IPA**

V SideStore otevři **Sources → Add Source** a vlož:

```text
https://raw.githubusercontent.com/GrgoPitic/NuvioMobile/cmp-rewrite/sidestore/source.json
```

Tento projekt je komunitní a nejde o oficiální distribuci
NuvioMedia.

</details>

<details>
<summary><strong>🇸🇰 Slovenčina</strong></summary>

### Slovenčina

Toto je **neoficiálny čistý nepodpísaný IPA build** Nuvio
pre iOS / iPadOS.

- Aktuálna verzia: **0.4.11**
- Minimálny systém: **iOS / iPadOS 16.1+**
- Podporované zariadenia: **iPhone & iPad**
- Distribúcia: **FULL**
- Podpis: **Unsigned IPA**

V SideStore otvor **Sources → Add Source** a vlož:

```text
https://raw.githubusercontent.com/GrgoPitic/NuvioMobile/cmp-rewrite/sidestore/source.json
```

Tento projekt je komunitný a nejde o oficiálnu distribúciu
NuvioMedia.

</details>

💜 **Thank you for supporting Nuvio and the community.**

---
