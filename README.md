# vscode-extensions

Utilities and recommended settings to make Visual Studio Code feel and behave more like IntelliJ IDEA.

## What this repository contains
- Small utilities, configuration snippets and recommendations to mimic IntelliJ behavior in VS Code.
- Keybindings fork: `vscode-shortcuts-plugin/vscode-intellij-idea-keybindings` (this repository is a fork of https://github.com/kasecato/vscode-intellij-idea-keybindings).
- Opinions and presets for editor navigation, search, refactorings and UI tweaks.

## Features
- IntelliJ-style keybindings (via the forked keybindings project).
- Suggested VS Code settings to adjust editor navigation, code completion and appearance.
- Recommended extensions and quick setup instructions to get an IntelliJ-like workflow.

## Quick install
1. Clone this repository:
    git clone <repo-url>
2. Open the folder in VS Code.
3. Install recommended extensions (see .vscode/extensions.json if present) or install the keybindings fork:
    - Install from the forked repo (open it and run "Install from VSIX" if a VSIX is provided) or follow the fork README for installation steps.
4. Apply suggested settings:
    - Merge relevant snippets from this repo into your `settings.json` and `keybindings.json`.

## Recommended extensions (examples)
- IntelliJ IDEA Keybindings (this repo's fork)
- JetBrains themes or high-contrast themes (for closer visual parity)
- EditorConfig
- Java/Scala/Python language support extensions as needed

## Configuration tips
- Import or apply the provided `keybindings.json` and `settings.json` snippets to align shortcuts and editor behavior.
- Use the Command Palette (Ctrl/Cmd+Shift+P) → "Preferences: Open Keyboard Shortcuts (JSON)" to merge keybindings.
- Reload VS Code after installing extensions or changing keybindings.

## Contributing
- Contributions and improvements are welcome.
- Open issues for bugs or feature requests.
- Submit pull requests with clear descriptions and small, focused changes.

## Fork notice
The keybindings package in this repo is a fork of https://github.com/kasecato/vscode-intellij-idea-keybindings. See that upstream project for original context and history.

## License
See the LICENSE file in this repository for license details.

---

For questions or help setting this up, open an issue in this repository.