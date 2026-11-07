# Homebriar 1.0 TEST
Native Android Satogaeri return-to-country puzzle. Android8+ (min26), target35. Package com.gg007.homebriar.

## Rules
Satogaeri: move each numbered circle once, in one straight horizontal or vertical track, by exactly its number of cell steps. Tracks cannot cross, overlap or pass over another starting circle. Each outlined country must contain exactly one final circle. Starting circles remain visible as route origins, cyan endpoints are final arrivals. This edition uses only positive numbered circles, no blank or zero circles. Select a numbered start, then tap its destination. Undo/reset/next/levels and saved home palette/country labels. Twelve unique 4x4 connected-country boards and distinct unique routes.

## Download and status
https://mega.co.nz/#!oEEECRYJ!igyr_VWMN1KoAhP2RjiDLrGhzLBjWN78uVX-ZJqSmCk
APK SHA256 db957a0ef35aa9feffc1d4724026dd462378ba007468d42e7ba16ba7d45b41ed; 20974 bytes. Original signing certificate SHA256 1651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. Anonymous download bytes match.

## Checks
Independent coordinate-ray/set oracle agrees with production step-walk/bitmask paths for all15552 partial/complete/invalid direction states and7440 assignment transitions from valid partial states. Twelve distinct connected four-country layouts and unique solutions. At least three circles per board have multiple geometric options before track/room constraints. Bounds, invalid levels/directions/array sizes, selection, solved lock, solve/undo/reverse-order replay pass. Actual archived generator regeneration and archived Java tests pass. Drawing-adapter start/destination taps, menu/settings/privacy/levels/next and saved preference/completion checks pass. Actual game/solved/menu/settings/privacy/levels drawing pixels inspected, not phone screenshots. Phone runtime, performance and external-browser handoff QA remain incomplete. Signed TEST, not final or Play published.

## Functional difference
Live803-entry registry,122 recovered partial READMEs and semantic review of all148 prior studio cards found no Satogaeri match. Potwillow sends numbered cargo any straight distance into three sum pots; circles contribute their numbers to pot totals. Homebriar instead fixes each circle's travel length and requires exactly one final circle in every all-covering country, with no cargo sums. Heronputt permits multiple shrinking-length shots toward designated holes and water constraints; Homebriar permits just one fixed straight displacement, no target holes or water. Known Nikoli Satogaeri genre, not a global invention; recovered corpus is partial. Rules https://www.nikoli.co.jp/en/puzzles/satogaeri/ https://www.atlasobscura.com/articles/puzzle-monday-satogaeri https://www.janko.at/Raetsel/Satogaeri/index.htm .

## Build
JDK17 and AndroidSDK35/build-tools35.0.0. python generate-levels.py reproduces levels.json. Board.java embeds the generated clues and solutions. javac -d /tmp/space-test src/com/gg007/homebriar/Board.java BoardTest.java and java -cp /tmp/space-test com.gg007.homebriar.BoardTest. bash build.sh builds an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to private original signing inputs. No credentials in source. Release build settings, signed TEST artifact, not final store release.

## Privacy and branding
Homebriar runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Home palette, country labels and solved-board marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 icon byte-equal to original. Menu studio https://ilanis-agent.github.io/gg-007-gaming/ and privacy.

## Preservation and websites
Complete source and APK privately preserved at https://files.instinct.com/lkzmkwnl5rvp-homebriar-source-archive, including exact cumulative149-card studio and published catalog/studio sources/updater. Repository https://github.com/iLanis-agent/homebriar holds README only; full Git source commit pending. Both website publications checked separately. No Pages settings change or Play rollout. November7,2026.
