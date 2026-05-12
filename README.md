# awesome-cli-skills

A curated registry of CLI tools and AI agent skills for WorkRail.

## Format

Each plugin entry is a list item with the pattern:
```
- **[name](repo-url)** `version` — description
```

Below the entry, indented sub-sections declare:

- **`**Binary**`** — Platform-specific download URLs. Each `[platform-key](url)` pair maps a known platform to a CLI binary download URL. Known platforms: `darwin-arm64`, `darwin-x64`, `linux-x64`, `linux-arm64`, `win-x64`, `win-arm64`.
- **`**Skills**`** — One or more SKILL.md references. Each `[skill-name](url)` pair names a skill and points to its SKILL.md definition. The skill name becomes the agent tool name. Multiple skills can share the same CLI binary.

## Registry

- **[officecli](https://github.com/iOfficeAI/OfficeCLI)** `v1.0.86` — OfficeCLI is the first and best Office suite purpose-built for AI agents to read, edit, and automate Word, Excel, and PowerPoint files. Free, open-source, single binary, no Office installation required.
  - **Binary**
    [darwin-arm64](https://github.com/iOfficeAI/OfficeCLI/releases/download/v1.0.86/officecli-mac-arm64)
    [darwin-x64](https://github.com/iOfficeAI/OfficeCLI/releases/download/v1.0.86/officecli-mac-x64)
    [linux-x64](https://github.com/iOfficeAI/OfficeCLI/releases/download/v1.0.86/officecli-linux-x64)
    [linux-arm64](https://github.com/iOfficeAI/OfficeCLI/releases/download/v1.0.86/officecli-linux-arm64)
    [win-x64](https://github.com/iOfficeAI/OfficeCLI/releases/download/v1.0.86/officecli-win-x64.exe)
    [win-arm64](https://github.com/iOfficeAI/OfficeCLI/releases/download/v1.0.86/officecli-win-arm64.exe)
  - **Skills**
    [officecli](https://raw.githubusercontent.com/iOfficeAI/OfficeCLI/main/SKILL.md)
