# AFSA Incoming Template

Public reference layout for per-user repositories under
[`ai-for-smart-agriculture`](https://github.com/ai-for-smart-agriculture).

**Live user repos** are named `user-{github_login}-incoming` and are **private**.
This template is copied when provisioning a new user repository.

---

## Directory tree

```text
user-{login}-incoming/
├── README.md
├── logs/
│   ├── README.md
│   └── {detection_id}.json          # optional .jpg thumbnail
├── orchards/
│   ├── README.md
│   ├── zh/index.json                # written when App locale = zh
│   └── en/index.json                # written when App locale = en
└── summary_images/
    ├── README.md
    ├── apple/
    ├── strawberry/
    └── other/
        └── immature/
```

---

## Locale rules

| App language | Orchard file | Path language |
|--------------|--------------|---------------|
| Chinese (`zh`) | `orchards/zh/index.json` | English folder names |
| English (`en`) | `orchards/en/index.json` | English folder names |

`logs/` and `summary_images/` always use **English** paths and folder names.

---

## Related projects

| Resource | Link |
|----------|------|
| Knowledge base | [yhlkxkzs/afsa-knowledge](https://github.com/yhlkxkzs/afsa-knowledge) |
| Inference models | [ai-agriculture-circuits-and-systems](https://github.com/ai-agriculture-circuits-and-systems) |
| Organization home | [ai-for-smart-agriculture](https://github.com/ai-for-smart-agriculture) |

---

## License

Template documentation only. User image and orchard data in private repos remain user/platform data.
