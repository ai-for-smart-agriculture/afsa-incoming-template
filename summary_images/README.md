# Summary images (`summary_images/`)

User-saved recognition thumbnails grouped by **English** fruit/category folder names.

## Folder naming

| Folder | Meaning |
|--------|---------|
| `apple/` | Apple |
| `strawberry/` | Strawberry |
| `other/` | Other / unknown fruit |
| `other/immature/` | Immature fruit state |

Each record is a pair:

- `{detection_id}.json` — metadata
- `{detection_id}.webp` or `.jpg` — image

Folder names are always English (`apple`, not `苹果`) so fleet scripts and
cross-locale search stay consistent.
