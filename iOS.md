# iOS

Primarly iPhone SE 2020 with iOS 14.0.1

## Apps (open-source)

### Terminal 

[iSH](https://ish.app/) — Alpine Linux i686 container with filesystem access via Files app

### Password Manager 

[KeePassium](https://apps.apple.com/pl/app/keepassium-keepass-passwords/id1435127111) — KeePass compatible

### OTP (2FA)

[Raivo OTP](https://apps.apple.com/pl/app/raivo-otp/id1459042137)

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

![](img/hp1.jpg?display=inline-block) ![](img/hp2.jpg?display=inline-block)
</details>
