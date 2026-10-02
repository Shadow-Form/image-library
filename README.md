# image-library
A growing collection of cloud, development, platform, language, and application icons, organized for easy use in GitHub READMEs, documentation, and architecture diagrams.

## Layout

```
icons/
├── cloud/        azure, aws, gcp, other
├── languages/    python, csharp, javascript, typescript, go, powershell
├── devtools/     vscode, git, github, docker, kubernetes, terraform
├── platforms/    windows, linux, macos
├── apps/         office/{excel, onenote, outlook, powerpoint, word}
│                microsoft-365/{defender, onedrive, sharepoint, teams}
│                it-service-management/ivanti-service-manager (approved for limited use in M365; no rights granted to repo visitors)
└── misc/         generic shapes, arrows, status indicators
metadata/         index.json, categories.yaml
examples/         embedding snippets
```

## Conventions

- One folder per icon: `icons/<category>/<group>/<name>/`
- Lowercase kebab-case names; files match the folder: `logic-apps/logic-apps.svg`, `logic-apps/logic-apps.png`
- SVG preferred; PNG at 256×256 with transparent background when SVG isn't available
- Add an entry to [metadata/index.json](metadata/index.json) for each icon:

```json
{
  "id": "microsoft-365-defender",
  "name": "Microsoft Defender",
  "path": "icons/apps/microsoft-365/defender",
  "formats": ["svg"],
  "tags": ["microsoft-365", "security", "endpoint-protection"],
  "source": "https://learn.microsoft.com/en-us/microsoft-365/solutions/architecture-icons?view=o365-worldwide",
  "sourceFile": "Defender-Icon-FY26.svg",
  "sourceVersion": "FY26 (download reference; no published pack version)",
  "license": "microsoft"
}
```

## Usage

See [examples/](examples/README.md).

## License

Original content is [MIT](LICENSE). Third-party icons remain the property of their owners. See [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) for terms and use restrictions.
