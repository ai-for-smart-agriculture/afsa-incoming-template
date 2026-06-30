# Recognition logs (`logs/`)

Stores detection records created by the AFSA mobile app.

## Files

| Pattern | Description |
|---------|-------------|
| `{detection_id}.json` | Structured result (species, disease, scores, timestamps) |
| `{detection_id}.jpg` | Optional thumbnail |

## Notes

- Paths and filenames use English.
- Records are merged on sign-in when the same GitHub account is used on a new device.
- Expired entries may be removed by retention workflows (`data_tier: log`).
