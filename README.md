# Skytrace releases

Binary packages only. No source code lives in this repository; it exists to serve the
update manifest that running copies of Skytrace poll, plus the archives it links to.

The program updates itself: open 检查更新 in the top bar and click 立即更新, so nothing
here has to be downloaded by hand. This repository is the fallback.

## 0.1.1

- Published: 2026-11-20T08:40:30Z
- Archive: [Skytrace-0.1.1-win64.zip](https://github.com/Yuki-Kitayama/Skytrace-releases/raw/main/files/Skytrace-0.1.1-win64.zip)
- Checksum: `2fe397db328c8567a714fec8b6882ac6278af510d1a15c1f0c9f57d7f4960eb1`

- `version.json` is fetched once a day, or on demand from the 检查更新 button.
- `files/` holds the zips. Unpack the whole folder over an existing installation:
  the GUI loads `backend-cli-*.exe` from beside itself, so a partial copy breaks.
