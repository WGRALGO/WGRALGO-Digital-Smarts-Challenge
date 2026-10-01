# Changelog

## v1.1.0 — 2026-10-01

- New scenario bank: 60 scenarios across AI Chatbots, Google, and YouTube, with a Mix mode.
- Rounds are now 10 scenarios; every answer scores (Best 3, Better 2, Good 1, Bad 0), with a review at the end.
- Real app look: black launch screen with the big WGRALGO logo (no white box on Android 12+), solid app bar, About / Privacy / Credits sheets.
- New launcher icon: the logo on black, sized to fit round, squircle, and square icon shapes.
- Android back button closes sheets, returns to the menu, and asks before exiting.
- Removed the external "play another game" link; a content security policy blocks all network access.
- Internet permission removed from the merged manifest.
- Signed with a new key. Uninstall v1.0.0 before installing v1.1.0.
- Added GitHub Actions debug builds and a signed release workflow with validation.

## v1.0.0 — 2026-05-26

- Initial GitHub-ready Android APK release.
- Added offline digital literacy challenge game.
- Added Bad / Good / Better / Best scenario format.
- Added shuffled 5-scenario rounds.
- Added ChatGPT Prompting, Google Search, YouTube How-To Search, Source Checking, and Digital Safety modes.
- Added 40+ built-in scenarios with a "why Best wins" lesson after every answer.
- Added Best Picks score tracking, progress bar, and final rating screen.
- Removed website navigation, social media, and fundraising bars from APK interface.
- Re-skinned APK in WGRALGO black-and-gold premium card UI.
- Repackaged under `org.wgralgo.digitalsmartschallenge`.
- Removed all network permissions — app is fully offline.
- Added GPLv3 license, privacy statement, contributors file, and README.
- Signed release APK with new dedicated keystore.
