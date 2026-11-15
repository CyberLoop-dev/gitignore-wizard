# Gitignore Wizard

Generate a starter `.gitignore` from common language and tooling presets.

## Included presets
- Python
- Node.js
- Visual Studio Code
- Windows and macOS clutter

## Usage
```bash
python gitignore_wizard.py python node vscode
python gitignore_wizard.py python --output .gitignore
```

The generator combines selected presets, removes duplicate lines, and preserves comments.

## License
MIT
