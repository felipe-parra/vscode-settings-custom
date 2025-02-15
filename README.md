# <img src="https://skillicons.dev/icons?i=vscode" height="40" alt="mongodb logo"  /> VS Code Settings

This repository contains my personal Visual Studio Code settings. These settings are optimized for JavaScript, TypeScript, JSON, HTML, and CSS development, ensuring a consistent and efficient coding experience.

## Features
- **Prettier as Default Formatter**: Ensures uniform formatting across JavaScript, TypeScript, JSON, HTML, and CSS.
- **Format on Save & Paste**: Automatically formats code upon saving or pasting.
- **Bracket Pair Colorization**: Enhances readability of nested code structures.
- **Optimized Editor UI**: Custom font size, line height, and disabled minimap for better focus.
- **Auto Save**: Saves files automatically after a short delay.
- **Explorer Tweaks**: Expanded folder structure for better navigation.
- **Custom Theme Customization**: Aesthetic title bar styling.

## Installation
To use these settings in your VS Code environment:

1. Open **VS Code**.
2. Navigate to **Settings** (File > Preferences > Settings or `Ctrl + ,`).
3. Click the **Open Settings (JSON)** button in the top right corner.
4. Copy and paste the contents of `settings.json` from this repository.
5. Save the file and restart VS Code if necessary.

## settings.json
```json
{
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": "explicit"
  },
  "editor.bracketPairColorization.enabled": true,
  "editor.fontSize": 16,
  "editor.formatOnPaste": true,
  "editor.guides.bracketPairs": true,
  "editor.lineHeight": 24,
  "editor.minimap.enabled": false,
  "editor.tabSize": 2,
  "editor.wordWrap": "on",
  "explorer.compactFolders": false,
  "files.autoSave": "afterDelay",
  "workbench.editor.enablePreview": false,
  "workbench.colorCustomizations": {
    "titleBar.activeBackground": "#007acc",
    "titleBar.activeForeground": "#ffffff"
  }
}
```

## Contributing
Feel free to submit pull requests or suggestions if you have improvements or additional settings to enhance the development experience.

## License
This project is licensed under the MIT License.

