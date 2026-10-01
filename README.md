# image-library
A growing collection of cloud, development, platform, language, and application icons, organized for easy use in GitHub READMEs, documentation, and architecture diagrams.

## Layout

```
icons/
├── cloud/        azure, aws, gcp, other
├── languages/    python, csharp, javascript, typescript, go, powershell
├── devtools/     vscode, git, github, docker, kubernetes, terraform
├── platforms/    windows, linux, macos
├── apps/         office/{outlook, excel, word, teams}
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
  "id": "azure-logic-apps",
  "name": "Logic Apps",
  "path": "icons/cloud/azure/logic-apps",
  "formats": ["svg", "png"],
  "tags": ["azure", "integration", "workflow"],
  "source": "https://learn.microsoft.com/azure/architecture/icons/",
  "license": "microsoft"
}
```

## Usage

See [examples/](examples/README.md).

## License

Original content is [MIT](LICENSE). Third-party icons remain the property of their owners. See [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).
