# Fitrail — Privacy-First Fitness, Sleep & Workout Tracker with Route Privacy

**Train smarter. Keep your movement yours. A free, privacy-first fitness app: encrypted on your device, with route privacy, a local coach, sleep insights and wearable sensor support.**

[![Live App](https://img.shields.io/badge/Live%20App-fitrail.lyfmail.com-teal)](https://fitrail.lyfmail.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-purple.svg)](https://github.com/lyfmail-official/fitrail/blob/main/LICENSE)
[![PWA](https://img.shields.io/badge/PWA-Installable-orange.svg)](https://fitrail.lyfmail.com)
[![Privacy](https://img.shields.io/badge/Privacy-Encrypted%20On%20Device-green.svg)](https://fitrail.lyfmail.com)
[![Maintained by LYF Mail](https://img.shields.io/badge/Maintained%20by-LYF%20Mail-red)](https://lyfmail.com)

A free project from [LYF Mail](https://lyfmail.com) — India's privacy-first digital wellness platform.

---

## 🏃 What Is Fitrail?

**Fitrail** is a free, **privacy-first fitness app** that keeps your **workouts, sleep and heart-rate data on your own device, encrypted** with a passphrase only you know. **Route privacy** lets you share a result without sharing your home address.

*Fitrail helps you train, recover and sleep better without handing your data to anyone.*

Built by [LYF Mail](https://lyfmail.com), a [privacy-first digital wellness platform](https://lyfmail.com) serving 50,000+ subscribers across India since 2020.

---

## 🧭 Why Fitrail Exists

- 📍 **Workout routes reveal where you live, work and spend time.**
- 😴 **Fitness and sleep data are deeply personal.**
- 📊 **Most fitness apps hold your data on their servers** and build accounts, profiles and sharing features around it.

Fitrail keeps data on your device **by default** and **asks before anything leaves**.

---

## ✨ Key Features

### 🔐 Encrypted Vault
Workouts and sleep are **encrypted on your device** with a passphrase only you know.

### 🗺️ Route Privacy
**Hide home and work**, round and fuzz coordinates, and **share a card instead of a map trace**.

### 🧠 Coach on Your Device
Training load, recovery and sleep insights are **calculated locally**, each tied to your own numbers.

### 📜 Consent Ledger
Every share, import and AI request is **logged and signed**, so you can prove what happened.

### ⌚ Wearable Sensors
Pair a **heart-rate strap, cadence sensor or power meter over Bluetooth**, or import from your watch.

### 🔀 Private or Hybrid Mode
**Private mode never sends anything.** Hybrid mode sends only redacted text, **after you approve a before-and-after preview**.

### 🕶️ Built for the Wrist
**Glance mode** shows one big number with haptic zone cues on a dark display. Use the watch version on a watch browser, or mount your phone on your arm or handlebars.

### 📥 Bring Your History
Import **Apple Health exports, Gadgetbridge databases, and FIT, GPX or TCX files**.

---

## ✅ Works With

- Heart-rate straps
- Garmin and Amazfit heart-rate broadcast
- Gadgetbridge
- Apple Health export
- FIT, GPX and TCX files
- Power meters
- Running cadence
- Phone GPS

---

## 🧬 Our Principles

| Principle | What it means |
|-----------|---------------|
| **Local by default** | Raw workouts and health data stay on your device unless you share them. |
| **Minimal disclosure** | Share summaries, not raw traces. |
| **Explicit consent** | Every AI request, share and sensor needs a clear purpose. |
| **No surveillance** | No ads, no third-party trackers, no hidden AI training. |

---

## 🚀 Quick Start Guide

### For Users
1. **Visit** [fitrail.lyfmail.com](https://fitrail.lyfmail.com) and tap **Open app** (or open the watch version on a watch browser).
2. **Create your vault** with a passphrase only you know.
3. **Record or import** a workout, or review last night's sleep.
4. **Share a card, not a map trace**, whenever you want to share a result.

### For Developers
```bash
git clone https://github.com/lyfmail-official/fitrail.git
cd fitrail
python -m http.server 8080   # or: npx serve .
```
Open `http://localhost:8080`. The page ships with a strict Content-Security-Policy (`default-src 'self'`), so keep scripts, styles and images first-party. See [`CONTRIBUTING.md`](CONTRIBUTING.md).

---

## 🌍 Who Uses Fitrail?

### 🏃 Runners & Cyclists
People who train outdoors and care about **location privacy**.

### 🏋️ Gym & Home Workout Enthusiasts
Anyone who wants a straightforward, private workout log.

### 😴 Sleep-Conscious Users
People who track rest as part of their routine.

### 🔒 Privacy-Conscious Users
Individuals who do not want fitness and location history in someone else's database.

### 🧑‍🏫 Coaches & Clubs *(coming next)*
Share approved metrics with a coach, never raw GPS.

---

## 🤝 Contributing to Fitrail

Fitrail welcomes contributions that respect our core principles:

- **Local by default** — raw workouts and health data stay on the device unless the user shares them.
- **Minimal disclosure** — share summaries, never raw traces or routes.
- **Explicit consent** — every AI request, share and sensor needs a clear purpose.
- **No surveillance** — no ads, no third-party trackers, no hidden AI training.
- **Privacy-first** — never introduce tracking, analytics or unnecessary data collection.
- **Accessibility-first** — every feature must work for users with disabilities.

Please read [`CONTRIBUTING.md`](CONTRIBUTING.md) and [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) before submitting pull requests. To report a vulnerability, see [`SECURITY.md`](SECURITY.md).

---

## 🏗️ The LYF Mail Ecosystem

Fitrail is one of **fifteen free privacy-first apps** built by [LYF Mail](https://lyfmail.com), a [digital wellness platform](https://lyfmail.com) from Varanasi, India, serving 50,000+ subscribers since 2020. Browse them all at [lyfmail.com/privacy-first-apps](https://lyfmail.com/privacy-first-apps), or explore our other projects:

| Project | Description | Live App | Repository |
|---------|-------------|----------|------------|
| **[LYF Mail](https://lyfmail.com)** | Privacy-first newsletters for health, wealth, career & mindfulness. | [lyfmail.com](https://lyfmail.com) | `lyfmail` |
| **[LYF Mail App](https://app.lyfmail.com)** | Installable app with newsletters, guides and free tools. | [app.lyfmail.com](https://app.lyfmail.com) | `lyfmail-pwa` |
| **[Ebb](https://ebb.lyfmail.com)** | Private period and fertility tracker. Data stays on your device. | [ebb.lyfmail.com](https://ebb.lyfmail.com) | `ebb` |
| **[Together](https://together.lyfmail.com)** | Silent shared presence for calm. No feed, no likes, no chat. | [together.lyfmail.com](https://together.lyfmail.com) | `together` |
| **[Rewriter](https://rewriter.lyfmail.com)** | Private narrative therapy writing companion with six guided phases. | [rewriter.lyfmail.com](https://rewriter.lyfmail.com) | `rewriter` |
| **[Offload](https://offload.lyfmail.com)** | Pre-sleep brain dump with pink noise, optional binaural beats and a dream journal. | [offload.lyfmail.com](https://offload.lyfmail.com) | `offload` |
| **[Mnemo](https://mnemo.lyfmail.com)** | Private encrypted second brain with on-device AI search and chat. | [mnemo.lyfmail.com](https://mnemo.lyfmail.com) | `mnemo` |
| **[Psychelog](https://psychelog.lyfmail.com)** | Encrypted integration journal with on-device insights and therapist export. | [psychelog.lyfmail.com](https://psychelog.lyfmail.com) | `psychelog` |
| **[TrustLens](https://trustlens.lyfmail.com)** | Check news, links and forwarded messages for misinformation before you share. | [trustlens.lyfmail.com](https://trustlens.lyfmail.com) | `trustlens` |
| **[LYF SOS](https://lyfsos.lyfmail.com)** | Offline emergency mesh network for Android. Built for India. | [lyfsos.lyfmail.com](https://lyfsos.lyfmail.com) | `lyfsos` |
| **[PDPR](https://pdpr.lyfmail.com)** | Public Dark-Pattern Registry. Document deceptive UX ethically. | [pdpr.lyfmail.com](https://pdpr.lyfmail.com) | `pdpr` |
| **[Signals](https://signals.lyfmail.com)** | Privacy-first analytics. Human vs. bot detection without cookies or fingerprinting. | [signals.lyfmail.com](https://signals.lyfmail.com) | `signals` |
| **[Custos](https://custos.lyfmail.com)** | Local-first guardian for sensitive financial data before it reaches AI. | [custos.lyfmail.com](https://custos.lyfmail.com) | `custos` |
| **[HireStack](https://hirestack.lyfmail.com)** | Nine free career tools for freelancers and job seekers. Works offline. | [hirestack.lyfmail.com](https://hirestack.lyfmail.com) | `hirestack` |
| **[Veilora](https://veilora.lyfmail.com)** | Six free tools for creators: clean image metadata, scan text, check before publishing. | [veilora.lyfmail.com](https://veilora.lyfmail.com) | `veilora` |

### 📚 Free Newsletters & Guides
- [Health & Wellness Guide](https://lyfmail.com/health-wellness-guide)
- [Personal Finance Guide](https://lyfmail.com/personal-finance-guide)
- [Career Development Guide](https://lyfmail.com/career-development-guide)
- [Creativity Resources](https://lyfmail.com/creativity-resources)
- [Mindfulness Practices](https://lyfmail.com/mindfulness-practices)

**Newsletter Signups:** [Health](https://health.signup.lyfmail.com) · [Finance](https://financing.signup.lyfmail.com) · [Career](https://career.signup.lyfmail.com) · [Creativity](https://creativity.signup.lyfmail.com) · [Personal Development](https://intuition.signup.lyfmail.com)

---

## 📜 License

Fitrail is released under the **MIT License**. You are free to use, modify and distribute it — including commercially. See [`LICENSE`](LICENSE) for full terms.

---

## 📫 Connect With Us

- **🌐 Website:** [lyfmail.com](https://lyfmail.com)
- **🏃 Fitrail App:** [fitrail.lyfmail.com](https://fitrail.lyfmail.com)
- **🛠️ All Privacy-First Apps:** [lyfmail.com/privacy-first-apps](https://lyfmail.com/privacy-first-apps)
- **📱 PWA:** [app.lyfmail.com](https://app.lyfmail.com)
- **📚 Documentation:** [docs.lyfmail.com](https://docs.lyfmail.com)
- **🎨 Brand Assets:** [github.com/lyfmail-official/lyfmail-brand-assets](https://github.com/lyfmail-official/lyfmail-brand-assets)
- **🐦 X / Twitter:** [LYF Mail](https://x.com/lyfmailcom)
- **📘 Facebook:** [LYF Mail](https://www.facebook.com/thelyfmail)
- **▶️ YouTube:** [LYF Mail](https://m.youtube.com/channel/UCurymhWrl2nkvv31uJMuc0g)
- **💼 LinkedIn:** [LYF Mail](https://www.linkedin.com/company/lyf-mail)
- **📧 General Email:** contact@lyfmail.com
- **🆘 Support:** [support.lyfmail.com](https://support.lyfmail.com)

---

*"Every Choice Shapes Tomorrow"*

**Maintained by [LYF Mail](https://lyfmail.com)** · Founded by [Ajay Kumar Chaudhary](https://github.com/lyfmail) · Varanasi, Uttar Pradesh, India · Since 2020

---

## 💬 Frequently Asked Questions

**Q: Where is my fitness data stored?**  
A: On your own device, encrypted with a passphrase only you know. Fitrail keeps data local by default and asks before anything leaves.

**Q: What is route privacy?**  
A: Route privacy means you can hide home and work, round and fuzz coordinates, and share a card instead of a map trace, so a shared workout does not reveal where you live.

**Q: What is the difference between Private and Hybrid mode?**  
A: Private mode never sends anything. Hybrid mode sends only redacted text, after you approve a before-and-after preview.

**Q: Which devices and files does Fitrail work with?**  
A: Heart-rate straps, Garmin and Amazfit heart-rate broadcast, Gadgetbridge, Apple Health exports, FIT, GPX and TCX files, power meters, running cadence and phone GPS.

**Q: Does Fitrail run ads or third-party trackers?**  
A: No. Fitrail has no ads, no third-party trackers and no hidden AI training.

**Q: Is Fitrail a medical device?**  
A: No. Fitrail is a fitness and wellness tool, not a medical device. Consult a healthcare professional before starting a new exercise programme or if you have concerns about your health or sleep.

**Q: Is Fitrail free to use?**  
A: Yes. Fitrail is free to use under the MIT License, a project by [LYF Mail](https://lyfmail.com).

**Q: Can I contribute to Fitrail?**  
A: Yes. We welcome developers, designers, writers, translators and accessibility advocates. Please read [`CONTRIBUTING.md`](CONTRIBUTING.md) and [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) first.

**Q: How do I report a bug or a security issue?**  
A: Open a [GitHub issue](https://github.com/lyfmail-official/fitrail/issues) for bugs. For security vulnerabilities, **do not** open a public issue — follow [`SECURITY.md`](SECURITY.md).

---

*This README is maintained by the LYF Mail team. For issues, feature requests or contributions, please visit our [GitHub repository](https://github.com/lyfmail-official/fitrail).*
