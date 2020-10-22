# iOS

Primarly iPhone SE 2020 with iOS 14.0.1

## Apps (open-source)

- [iSH](https://ish.app/) — Alpine Linux i686 container with filesystem access via Files app
- [KeePassium](https://apps.apple.com/pl/app/keepassium-keepass-passwords/id1435127111) — KeePass compatible
- [Raivo OTP](https://apps.apple.com/pl/app/raivo-otp/id1459042137) — 2FA
- [Unstoppable Wallet](https://apps.apple.com/app/bank-bitcoin-wallet/id1447619907) — Bitcoin, Ethereum and other crypto
- [Nicegram](https://apps.apple.com/app/id1457369322) — Telegram client with advanced features
- [//afone](https://apps.apple.com/pl/app/afone/id1470424336) — SIP (VoIP) client with minimalistic design

## Troubleshooting

<details>
<summary>KeePass database sync over SSH</summary>

Use iSH and rsync (set short aliases in your shell for uploading and downloading database)
</details>

<details>
<summary>Personal Hotspot is missing in Settings</summary>

Settings → Mobile Data → _Your data plan here_ → Mobile Data Network

Fill your operator APN settings into **Peronal Hotspot** section. Usually it's just `internet` without login and password).

Then re-enable broadband (airplane mode on then off) and here you go!

<p style="display: flex; flex-wrap: wrap;">
<img src="img/hp1.jpg" style="max-width: 300px; margin: 0 0.5em 0.5em 0">
<img src="img/hp2.jpg" style="max-width: 300px; margin: 0 0.5em 0.5em 0">
</p>
</details>

