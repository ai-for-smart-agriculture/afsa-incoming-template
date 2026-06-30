# Orchards (`orchards/`)

Long-term orchard profile data. The app maintains **two locale copies**:

| Directory | When updated |
|-----------|--------------|
| `orchards/zh/index.json` | App UI language = Chinese (`zh`) |
| `orchards/en/index.json` | App UI language = English (`en`) |

Each `index.json` contains an `orchards` array with block metadata (name, location,
fence, fruit type, planting method, etc.).

Only the file matching the **current app language** is written on save; the other
locale is not overwritten unless the user switches language and saves again.
