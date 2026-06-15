# AppVersions

Public version manifest for Enerzinx applications.

This repository holds a single file — `versions.json` — that each Enerzinx
desktop application polls on startup to check whether a newer version is
available. When a newer version is detected, the application shows a
dismissible update banner with a link to the release notes.

## versions.json structure

```json
{
  "applications": {
    "ModelValidator": {
      "latest_version": "6.1.2.2",
      "release_date": "2026-06-15",
      "release_notes_url": "https://...",
      "release_notes": "Plain-text summary of changes in this version.",
      "download_url": ""
    },
    "ModelValidatorExternal": {
      ...
    }
  }
}
