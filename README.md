# Lantern — Changelog

This repository hosts the changelog for [Lantern](https://your-app-store-link), a nightly condition log for Android (iOS coming later).

The changelog is fetched in-app and displayed in the Keeper screen under About → Changelog.

## Format

```json
[
  {
    "version": "1.0.0",
    "date": "28 April 2026",
    "changes": [
      { "type": "new", "text": "Description of change" },
      { "type": "improved", "text": "Description of improvement" },
      { "type": "fix", "text": "Description of fix" },
      { "type": "removed", "text": "Description of removal" }
    ]
  }
]
```

## Change types

| Type | Meaning |
|------|---------|
| `new` | New feature or addition |
| `improved` | Enhancement to an existing feature |
| `fix` | Bug fix |
| `removed` | Feature or behaviour removed |

## File

[log.json](./log.json)
