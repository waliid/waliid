<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="/assets/hero-dark.svg">
    <img src="/assets/hero-light.svg" width="100%" alt="Walid Kayhal, Apple engineer building video players for iOS, tvOS and macOS. The name streams in like an adaptive video, from 240p up to 2160p.">
  </picture>
</p>

<p align="center">
  <a href="https://walid.kayhal.fr"><img src="https://img.shields.io/badge/walid.kayhal.fr-5E5CE6?style=for-the-badge&logo=safari&logoColor=white" alt="Website"></a>
  <a href="https://www.linkedin.com/in/walid-kayhal-3b3376a4/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://github.com/SRGSSR/pillarbox-apple"><img src="https://img.shields.io/badge/Pillarbox-F05138?style=for-the-badge&logo=swift&logoColor=white" alt="Pillarbox"></a>
  <a href="https://github.com/SRGSSR/castor"><img src="https://img.shields.io/badge/Castor-8B5A2B?style=for-the-badge&logo=googlecast&logoColor=white" alt="Castor"></a>
</p>

## `whoami`

```swift
struct Walid: AppleEngineer {
    let basedIn     = "Geneva 🇨🇭"
    let worksAt     = "SRG SSR / RTS"
    let experience  = "10+ years shipping Apple apps"
    let platforms: [Platform] = [.iOS, .tvOS, .macOS]
    let obsession   = "Video playback & streaming"
    let codingSince = "age 16"
    let speaks      = ["🇫🇷 French", "🇬🇧 English", "🇲🇦 Moroccan Arabic"]

    var mindset: [Trait] { [.creative, .adaptable, .openMinded, .teamPlayer] }
}
```

## 🎬 Now playing

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>▶️ <a href="https://github.com/SRGSSR/pillarbox-apple">Pillarbox</a></h3>
      The open-source video player SDK of SRG SSR for iOS &amp; tvOS.<br><br>
      <sub>📊 Analytics · 🩺 Monitoring · 🖼️ Picture in Picture · 🏷️ Metadata · 📚 Docs</sub>
    </td>
    <td width="50%" valign="top">
      <h3>🦫 <a href="https://github.com/SRGSSR/castor">Castor</a></h3>
      An SDK for delightful Google Cast integration on iOS, created at RTS.<br><br>
      <sub>📡 Google Cast · 🧩 First-class SwiftUI · 🔀 Local ↔ remote playback · 🎛️ Mini player</sub>
    </td>
  </tr>
</table>

## 📊 Stats for nerds

<table>
  <tr>
    <td><img src="/github-metrics.svg" alt="GitHub metrics"></td>
    <td><img src="/metrics.plugin.isocalendar.fullyear.svg" alt="Isometric commit calendar"></td>
  </tr>
</table>

---

```swift
// ⏹ End of stream. What's next?
switch viewer.intent {
case .collaborate: open(.linkedIn)
case .learnMore:   open(.website)
case .replay:      player.seek(to: .zero)
}
```

<p align="center">
  <a href="https://www.linkedin.com/in/walid-kayhal-3b3376a4/"><b>💬 Collaborate</b></a>
  &nbsp;·&nbsp;
  <a href="https://walid.kayhal.fr"><b>🌐 Learn more</b></a>
  &nbsp;·&nbsp;
  <a href="#"><b>⏮ Replay</b></a>
</p>
