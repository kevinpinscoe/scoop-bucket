# scoop-bucket

Scoop manifests for applications and tools I author or maintain.

## Status

Production

## Installing Scoop

If you don't have Scoop installed, run the following in PowerShell:

```powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
```

## Adding this bucket

```powershell
scoop bucket add kevinpinscoe https://github.com/kevinpinscoe/scoop-bucket
```

## Available tools

| Tool | Description |
|---|---|
| `metar-tool` | METAR aviation weather decoder |

## Installing a tool

```powershell
scoop install kevinpinscoe/metar-tool
```

## Updating a tool

```powershell
scoop update metar-tool
```

## Repository Layout

```
scoop-bucket/
├── bucket/          # Scoop manifests (JSON, one per tool — written by GoReleaser)
├── .gitignore
├── LICENSE
└── README.md
```

## License

MIT — see [LICENSE](LICENSE).

## Contributing & Reporting Issues

Bug reports, feature requests, security disclosures, and contributions are all
welcome. I keep these guidelines in one place for all my projects:

- **How to contribute or report an issue:** https://github.com/kevinpinscoe/how-to-contribute
- **Report a security vulnerability:** do not open a public issue. Use the
  **"Report a vulnerability"** button on this repository's **Security** tab, or
  see the [security policy](https://github.com/kevinpinscoe/how-to-contribute/blob/main/SECURITY.md).
