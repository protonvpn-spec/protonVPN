🇨🇳 [中文](README.md) | 🇺🇸 English | 🇷🇺 [Русский](README_RU.md)

#### Proton VPN has been working unreliably recently. Recommended alternative: [vpnacademy.com](https://vpnacademy.com/?utm_source=github&utm_campaign=git_protonvpn)</br>

Official website: [protonvpn.com](https://protonvpn.com)</br>
Proton VPN login: [account.protonvpn.com/login](https://account.protonvpn.com/login)</br>
Create a free account: [account.protonvpn.com/signup](https://account.protonvpn.com/signup)</br>
All downloads: [protonvpn.com/download](https://protonvpn.com/download)</br>

### Introduction

Proton VPN is a Swiss, open-source VPN from **Proton AG** in Geneva — the company behind Proton Mail, Proton Drive, Proton Calendar, Proton Pass and Lumo. It launched on 22 May 2017 and advertises **20,000+ servers in 140+ countries**, more than 100 million Proton accounts, and a free VPN plan with unlimited data, no ads and no credit card required.

### Proton VPN download — all apps

Every Proton VPN app is free to download, and one Proton account signs you in to all of them.

| Platform | Download | Notes |
| -------- | -------- | ----- |
| **Windows** (PC) | [Download](https://protonvpn.com/download-windows) | Installer for Windows 10 and 11 |
| **macOS** | [Download](https://protonvpn.com/download-macos) | Apple silicon and Intel |
| **Linux** | [Download](https://protonvpn.com/download-linux) | GTK app plus Proton VPN CLI |
| **Android** | [Download](https://protonvpn.com/download-android) | Google Play or direct APK |
| **iOS / iPadOS** | [Download](https://protonvpn.com/download-ios) | App Store |
| **Android TV** | [Download](https://protonvpn.com/download-androidtv) | Also on Amazon Fire TV |
| **Apple TV** | [Download](https://protonvpn.com/download-appletv) | tvOS app |
| **Chromebook** | [Download](https://protonvpn.com/download-chromebook) | ChromeOS |
| **Chrome / Firefox** | [Chrome](https://protonvpn.com/download-chrome-extension) · [Firefox](https://protonvpn.com/download-firefox-extension) | Browser extension |

Source code for every client is published on GitHub: [github.com/ProtonVPN](https://github.com/ProtonVPN)

### How to install and sign in

1. Download the Proton VPN app for your platform from the table above.
2. Create a free Proton account — the same login works for Proton VPN, Proton Mail, Proton Drive and Proton Pass.
3. Open the app, sign in, and press **Quick Connect** for the fastest server, or pick a country from the list.
4. Optionally turn on NetShield and the kill switch, or switch the protocol to Stealth if your network blocks VPN traffic.

No configuration files or manual setup are needed on any desktop or mobile app; routers (DD-WRT, Tomato, AsusWRT, pfSense) can be configured by hand.

### Server network

The network is built on bare-metal servers that Proton controls directly — physical machines with full-disk encryption rather than virtual instances — with links up to 10 Gbps and total capacity above 1 Tbps. Alongside the standard fleet there are **Secure Core** entry servers in Switzerland, Iceland and Sweden, one-click **Tor over VPN** servers for .onion access, P2P servers for torrenting, and streaming-optimised exits. **Smart Routing** covers countries that are hard to host in or actively censored.

### Plans

| Plan | Devices | Servers | Monthly | 1-year | 2-year |
| ---- | ------- | ------- | ------- | ------ | ------ |
| **Proton Free** | 1 | 10 countries, auto-assigned | $0 | $0 | $0 |
| **Proton VPN Plus** | 10 | 20,000+ in 140+ countries | $9.99/mo | $3.99/mo | $2.99/mo |
| **Proton Unlimited** | 10 | 20,000+ in 140+ countries | $12.99/mo | $9.99/mo | $7.99/mo |

Proton Unlimited adds Proton Mail, Proton Drive (500 GB), Proton Calendar and Proton Pass. Paid plans include a 30-day money-back guarantee; prices vary by region and promotion.

### Payments and refunds

Proton accepts all major credit and debit cards, PayPal, Apple Pay (macOS Safari and iOS), Google Pay, and **Bitcoin** — the most private option, available after you create a free account first. Cash is accepted by post in CHF, USD or EUR, as is bank transfer through UBS Switzerland. Core currencies are CHF, USD and EUR, with local billing in AUD, BRL, CAD, GBP, HKD, JPY, KRW, PLN and SGD on card and wallet payments. The 30-day money-back guarantee is **prorated** — cancel halfway through and you are credited only for the unused days — and cash and bank-transfer subscriptions cannot be refunded at all. Details: [protonvpn.com/support/payment-options](https://protonvpn.com/support/payment-options).

### Features

* **Secure Core** — multi-hop routing entering through Proton-owned servers in privacy-friendly countries
* **Stealth** — WireGuard-over-TLS obfuscation that looks like ordinary HTTPS and defeats deep packet inspection; on every plan, including the free one
* **NetShield** — DNS-level ad, tracker and malware blocker (paid)
* **VPN Accelerator** — up to 400% faster speeds, on by default (paid)
* **Kill switch**, split tunneling, port forwarding, Tor over VPN, DNS leak protection, Alternative Routing

Protocols: WireGuard (default), OpenVPN, Stealth and Smart Protocol, with AES-256 encryption, 4096-bit RSA key exchange and HMAC SHA-384.

### Speed, streaming and torrenting

WireGuard is the default protocol and the fastest of the three; independent testing has clocked Proton VPN at roughly 700 Mbps on it, which is enough for 4K streaming, gaming and large downloads. **VPN Accelerator** uses multi-threading and BBR flow control to recover speed on long-distance and unreliable connections, while Stealth trades roughly 10–35% of peak throughput for its obfuscation layer.

On paid plans the streaming-optimised servers reliably open more than a dozen Netflix libraries — including the US, UK, Canada, Japan and Germany — along with Hulu, Disney+, BBC iPlayer and YouTube, in HD and 4K. The free plan does not unblock Netflix. For torrenting, the P2P servers combined with port forwarding on Windows, macOS and Linux give the best results.

### Privacy and audits

Proton is based in Switzerland, outside the Five and Fourteen Eyes alliances and under one of the strongest data-protection laws in the world. Its **no-logs policy** has passed five consecutive annual audits by Securitum (2022–2026), each published in full without an NDA, and Proton also holds a SOC 2 Type II attestation and ISO 27001 certification. Its transparency report records 458 Swiss legal orders received since 2017 — every one denied, because no identifying logs exist to hand over. All apps are open source, independently audited, and covered by a bug bounty.

### Free VPN plan

Proton's free VPN is not a trial: unlimited data, 1 device, medium speed priority and 10 auto-assigned countries — the exit country cannot be chosen. Stealth and Alternative Routing are included; NetShield, Secure Core and P2P are not. Download it from [protonvpn.com/free-vpn](https://protonvpn.com/free-vpn).

### Proton VPN for Business

Business and Enterprise plans run roughly $6.99–$12.99 per user per month on annual billing and add central user management plus **dedicated IP addresses** — available in 21 locations for about $39.99/month per dedicated server, something the consumer plans do not offer. Proton also runs discount programmes for newsrooms and nonprofits covering the whole suite, and through the Proton Foundation has backed organisations including the Freedom of the Press Foundation and the International Federation of Journalists' Safety Fund. See [proton.me/business/vpn](https://proton.me/business/vpn).

### Support

A searchable help centre carries setup and troubleshooting guides, and email and ticket support is available on every plan; paid plans add priority support and live chat, though chat is not staffed around the clock. Service incidents are posted at [status.proton.me](https://status.proton.me), and [r/ProtonVPN](https://www.reddit.com/r/ProtonVPN/) is an active community. Contact: [protonvpn.com/support/contact](https://protonvpn.com/support/contact).

### Other Proton apps

One Proton account covers the whole suite: [Proton Mail](https://proton.me/mail) (formerly ProtonMail), [Proton Drive](https://proton.me/drive), [Proton Pass](https://proton.me/pass), [Proton Authenticator](https://proton.me/authenticator) and [Lumo](https://lumo.proton.me), Proton's private AI assistant. Manage everything at [account.proton.me](https://account.proton.me/login).

### Proton VPN in China

If Proton VPN will not connect behind the Great Firewall, switch the protocol to **Stealth** and turn on **Alternative Routing** — both work on the free plan. Set this up before you arrive, and connect through Japan, Hong Kong or Singapore for the lowest latency. Proton itself states that no VPN can guarantee 100% reliability in China and puts its own odds in restrictive countries at roughly 50%: it is built for privacy, not for censorship circumvention, so keep a backup. Troubleshooting guides: [protonvpn.com/support](https://protonvpn.com/support).
