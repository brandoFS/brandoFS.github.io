# brandofs.github.io

The root of the GitHub Pages domain. It exists for the two files phones read before they let a link open an app:

- `.well-known/assetlinks.json`: Android App Links. The package `com.brandomadden.podolski` and the SHA-256 of its
  signing certificates (the release upload key, printed by the Android release workflow's "Build the signed release
  APK" step, and the local debug key).
- `.well-known/apple-app-site-association`: iOS Universal Links. Team `73SSFVPVSK`, bundle `com.brandomadden.podolski`.

Both cover only `/fantasy-fussball/join/` (league invite links). The join page itself and the privacy policy live in
[brandoFS/fantasy-fussball](https://github.com/brandoFS/fantasy-fussball). `.nojekyll` makes Pages serve `.well-known`.
