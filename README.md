# FanYun English — release channel

Release metadata and hosted assets for the English-market FanYun build
(`com.aufesta.fanyun.en`). The app polls `version.json` on the `local`
build channel; store builds never self-update.

- `version.json` — latest build metadata (`versionCode`/`versionName`,
  `apkUrl` → GitHub Release asset, `notes`) plus the optional self-serve
  ad spec (`ad`, `adMedia`; both `enabled:false` ships an ad-free build).
- `fanyun-en-<version>-<date>.apk` — signed release APK; also attach it to
  a matching GitHub Release tag `v<versionName>` so `apkUrl` resolves.
- `privacy_policy_en.txt` — the privacy policy; Play Console URL:
  https://raw.githubusercontent.com/AufestaCan/fanyun-release/main/privacy_policy_en.txt
- `share.png` — recommend-a-friend QR (points at this repo).
- `icon.png` — brand icon referenced by the `ad.icon` slot.
