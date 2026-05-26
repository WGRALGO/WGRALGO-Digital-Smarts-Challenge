# WGRALGO Digital Smarts Challenge

Digital Smarts Challenge is a free educational Android app from **The Wealth Gap Resolution Algorithm™ Inc.** It helps users practice stronger ChatGPT prompts, Google searches, YouTube how-to searches, source checking, and digital safety habits through quick **Bad / Good / Better / Best** scenarios.

- **Version:** 1.0.0
- **Package:** `org.wgralgo.digitalsmartschallenge`
- **Platform:** Android (offline, sideload via APK)
- **Website:** https://thewealthgapresolutionalgorithm.org/digital-smarts-challenge/
- **License:** GPL-3.0-or-later

---

## Features

- Bad / Good / Better / Best answer format — only **Best** scores.
- 5 shuffled scenarios per round.
- 40+ built-in scenarios across 5 categories:
  - **ChatGPT Prompts**
  - **Google Searches**
  - **YouTube How-To Searches**
  - **Source Checking**
  - **Digital Safety**
- Instant feedback with a "why Best wins" lesson after every answer.
- Best Picks score tracking, progress bar, and final rating screen.
- Black + gold premium card UI, phone and tablet responsive.
- **100% offline.** No accounts, no ads, no analytics, no trackers, no data leaves your device.

## Screenshots

See [`/screenshots`](./screenshots).

## How to install (sideload)

1. Download the latest signed APK from the [Releases](../../releases) page.
2. On your Android device, allow installs from unknown sources for your file manager / browser.
3. Tap the APK to install.
4. Open **Digital Smarts Challenge** from your app drawer.

### Verify the APK
```
sha256sum DigitalSmartsChallenge-v1.0.0.apk
```
Compare against `DigitalSmartsChallenge-v1.0.0.apk.sha256` in the release.

## How to build from source

Requirements:
- Node.js 18+
- Android SDK + build-tools 34+
- Java 17

```
git clone https://github.com/WGRALGO/WGRALGO-Digital-Smarts-Challenge.git
cd WGRALGO-Digital-Smarts-Challenge
npm install
npx cap sync android
cd android
./gradlew :app:assembleDebug      # debug build
./gradlew :app:assembleRelease    # release (requires keystore.properties)
```

Release signing is configured via `android/keystore.properties` (not committed) or the env vars `DSC_KEYSTORE_FILE`, `DSC_KEYSTORE_PASSWORD`, `DSC_KEY_ALIAS`, `DSC_KEY_PASSWORD`.

## Privacy summary

- No account required.
- No ads, analytics, trackers, or crash reporting.
- No data is sent to WGRALGO or any third party.
- No personal data is collected.
- The app declares **no network permission** — it runs fully offline.

See [PRIVACY.md](./PRIVACY.md) for the full statement.

## Educational disclaimer

Digital Smarts Challenge is for **educational awareness only**. It does not provide legal, financial, medical, cybersecurity, technical, or professional advice. The examples are simplified learning scenarios. Users should verify important information through trusted sources and qualified professionals when needed.

## License

This project is released under the **GNU General Public License v3.0**. See [LICENSE](./LICENSE).

## Contributors

See [CONTRIBUTORS.md](./CONTRIBUTORS.md).
