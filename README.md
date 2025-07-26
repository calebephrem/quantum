# QUANTUM THEME FOR VSCODE

> Best blue, lime, yellow, purple and cyan color comboed theme!

![Preview](https://github.com/pandaproggit/quantum/blob/main/assets/screenshot.png)

### 🎨 The Theme...

- The Quantum theme comes with 2 versions: **Quantum** and **Quantum Dark**. Both of them are dark themes, but **Quantum Dark** is even darker.

- If you don't like italic (cursive) fonts in your code, there are themes included for you too: **Quantum (non-italicized)** and also **Quantum Dark (non-italicized)**, which is a darker clone.

### ⬇️ Installation

1. Open Extensions by clicing on the extension icon on the left sidebar panel in your VS Code
2. Search **Quantum**
3. Install the one by _PandaProg_
4. Press `ctrl+shift+P` to expand the command pallete (`cmd+shift+P` on mac)
5. Go under `Preferences: Color Theme`
6. Search **Quantum**
7. Then click on `Quantum` (or other variants of it)
8. Give the [repo](https://github.com/pandaproggit/quantum) a ⭐star

Walla! You have the Quantum theme activated!

### ⚙️ Recommended Settings

These are just settings that are recommended to make the theme even look better ✨

Edit these in _settings.json_ file in your VS Code. Expand the command pallete (`ctrl+shift+P`) and go under `Preferences: Open User Settings (JSON)`.

The settings under _optional_ are the settings that you can add if you want, but you can also ignore if you don't want them (the ones under _optional_ are not that important 🙃).

```jsonc
{
  "workbench.colorTheme": "Quantum", // Or other variants of Quantum theme listed
  // Download Fluent Icons extension
  "workbench.productIconTheme": "fluent-icons",
  // Download Material Icon Theme extension
  "workbench.iconTheme": "material-icon-theme",
  "material-icon-theme.files.color": "#90a4ae",
  "material-icon-theme.folders.color": "#e0c060",

  // Appearance
  // Download and install the font for free from https://github.com/willfore/vscode_operator_mono_lig
  "editor.fontFamily": "Operator Mono Lig, Cascadia Code, JetBrains Mono, Fira Code, monospace",
  "editor.letterSpacing": 0.5, // Don't add this if you are using vanilla monospace
  "editor.tabSize": 2, // 3 is also fine
  "editor.fontWeight": "normal",
  "editor.cursorWidth": 0, // 0 To go with the default setting (2 -> default), 3 is also fine
  "editor.cursorStyle": "line",
  "editor.cursorBlinking": "expand",
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.fontLigatures": true,
  "files.trimTrailingWhitespace": true,
  "editor.wordWrap": "on",
  "editor.quickSuggestions": {
    "strings": "inline"
  },
  "editor.hover.delay": 500,
  "terminal.integrated.fontFamily": "JetBrains Mono, Operator Mono Lig, Cascadia Code, Fira Code, monospace",
  "terminal.integrated.cursorStyle": "line",
  "terminal.integrated.cursorWidth": 2,
  "terminal.integrated.fontLigatures.enabled": true,

  // Formatting
  // Download the Prettier extension if you haven't already
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "prettier.singleQuote": true,
  "editor.formatOnSave": true, // this one is optional
  "prettier.eslintIntegration": true,
  "eslint.run": "onType",
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },

  // Remove or comment out all other color customizations and follow Quantum theme :)
  "workbench.colorCustomizations": {},

  // OPTIONAL
  "editor.minimap.enabled": false,
  "editor.guides.bracketPairs": false,
  "editor.acceptSuggestionOnEnter": "off",
  "editor.padding.top": 20,
  "files.autoSave": "off",
  "explorer.confirmDragAndDrop": false,
  "terminal.integrated.enableMultiLinePasteWarning": "never"
}
```

> Again, you can download and install the _Operator Mono Lig_ font for free from https://github.com/willfore/vscode_operator_mono_lig.

### 🛠️ If You Want To Customize The Theme

- First clone the [github repository](https://github.com/pandaproggit/quantum).
- Then you can modify the _json_ files under the **themes** folder by coming up with your own color combos!
- If you are interested, you can view some [docs](https://code.visualstudio.com/api/extension-guides/color-theme) on how to do it

```bash
git clone https://github.com/pandaproggit/quantum.git
```

🧐 Please let me know if you've caught some kinda funky thing, because this theme is new, and there are so many languages and VS Code parts that I don't use.

⭐ Don't forget to [star the repo](https://github.com/pandaproggit/quantum) to support me! Thanks 😁

**Enjoy! 😎**
