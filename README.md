# Skytrace releases

Binary packages only. No source code lives in this repository; it exists to serve the
update manifest that running copies of Skytrace poll, plus the archives it links to.

The program updates itself: open 妫€鏌ユ洿鏂?in the top bar and click 绔嬪嵆鏇存柊, so nothing
here has to be downloaded by hand. This repository is the fallback.

## 0.1.0

- Published: 2026-11-20T03:44:39Z
- Archive: [Skytrace-0.1.0-win64.zip](https://github.com/Yuki-Kitayama/Skytrace-releases/raw/main/files/Skytrace-0.1.0-win64.zip)
- Checksum: `3e2ba9e038ec887dfa95f8564d668f097efb035bf1f1f3587245f4f65d49ba8c`

- `version.json` is fetched once a day, or on demand from the 妫€鏌ユ洿鏂?button.
- `files/` holds the zips. Unpack the whole folder over an existing installation:
  the GUI loads `backend-cli-*.exe` from beside itself, so a partial copy breaks.
