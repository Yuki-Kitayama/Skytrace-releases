# Skytrace releases

Binary packages only. No source code lives in this repository; it exists to serve the
update manifest that running copies of Skytrace poll, plus the archives it links to.

- `version.json` is fetched once a day, or on demand from the 妫€鏌ユ洿鏂?button.
- `files/` holds the zips. Unpack the whole folder over an existing installation:
  the GUI loads `backend-cli-*.exe` from beside itself, so a partial copy breaks.
