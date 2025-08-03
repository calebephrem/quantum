# ⚛️ QUANTUM THEME FOR VSCODE!

> Best blue, lime, yellow, purple and cyan color comboed theme!

![Preview](https://github.com/pandaproggit/quantum/blob/main/assets/screenshot.png)

## 🎨 The Quantum ~~Physics~~ Theme ...

- Quantum theme comes with 2 versions: **Quantum** and **Quantum Dark**. Both of them are dark themes, but **Quantum Dark** is even darker.

- If you want to see more semi-transparent borders in your workplace, there is also bordered versions of the theme: **Quantum (bordered)** and **Quantum Dark (bordered)**.

- If you don't want to see italic (cursive) fonts in your code, there are themes included for you too: **Quantum (non-italicized)** and also **Quantum Dark (non-italicized)**.

- Generally, Quantum theme provides:

<table>
  <thead>
    <th>Theme</th>
    <th>Description</th>
    <th></th>
  </thead>
  <tbody>
    <tr>
      <td>Quantum</td>
      <td>Default, preferred, legendary</td>
      <td>💪</td>
    </tr>
    <tr>
      <td>Quantum Dark</td>
      <td>Darker version of "Quantum"</td>
      <td>👻</td>
    </tr>
    <tr>
      <td>Quantum Bordered</td>
      <td>Perfect clone of "Quantum", but with additional borders</td>
      <td>🤠</td>
    </tr>
    <tr>
      <td>Quantum Dark Bordered</td>
      <td>Quantum Dark + additional borders</td>
      <td>🚫</td>
    </tr>
    <tr>
      <td>Quantum Non-Italicized</td>
      <td>Quantum theme for italic haters</td>
      <td>😼</td>
    </tr>
    <tr>
      <td>Quantum Dark Non-Italicized</td>
      <td>Italic-less version of Quantum Dark</td>
      <td>🥸</td>
    </tr>
  </tbody>
</table>

## ⬇️ Installation

1. Open Extensions by clicking on the extension icon on the left sidebar panel in your VS Code
2. Search **Quantum**
3. Install the one by _PandaProg_
4. Press `ctrl+shift+P` to expand the command palette (`cmd+shift+P` on mac)
5. Go under `Preferences: Color Theme`
6. Search **Quantum**
7. Then click on `Quantum` (or other variants of it)
8. Give the [repo](https://github.com/pandaproggit/quantum) a ⭐star

🔥 Walla! You have the Quantum theme activated! ⚡

## ⚙️ Recommended Settings

These are just settings that are recommended to make the theme even look better ✨

Edit these in _settings.json_ file in your VS Code. Expand the command palette (`ctrl+shift+P`) and search `Preferences: Open User Settings (JSON)`.

The settings under _optional_ are the settings that you can add if you want, but you can also ignore if you don't want them (the ones under _optional_ are not that important 🙃).

```jsonc
{
  // Theme
  "workbench.colorTheme": "Quantum", // or other variants of Quantum theme listed
  // download Fluent Icons extension
  "workbench.productIconTheme": "fluent-icons",
  // download Material Icon Theme extension
  "workbench.iconTheme": "material-icon-theme",
  "material-icon-theme.hidesExplorerArrows": true,
  "material-icon-theme.files.color": "#9fafaf",
  // If you want folders to look similar to windows folder, instead of #40a0f0 use #e0c060
  "material-icon-theme.folders.color": "#40a0f0",

  // Appearance
  // Download and install the font for free from https://github.com/willfore/vscode_operator_mono_lig
  "editor.fontFamily": "Operator Mono Lig, Cascadia Code, JetBrains Mono, Fira Code, monospace",
  "editor.letterSpacing": 0.5, // don't add this if you are using vanilla monospace
  "editor.fontWeight": "normal",
  "editor.fontLigatures": true,
  "editor.glyphMargin": true,
  "editor.tabSize": 2, // 3 is also fine
  "editor.cursorStyle": "line",
  "editor.cursorBlinking": "expand",
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.cursorWidth": 0, // 0 is default setting (default = 2), 3 is also fine
  "editor.guides.bracketPairs": false,
  "editor.wordWrap": "on",
  "breadcrumbs.enabled": false,
  "editor.hover.delay": 500,
  "files.trimTrailingWhitespace": true,
  "terminal.integrated.fontFamily": "JetBrains Mono, Operator Mono Lig, Cascadia Code, Fira Code, monospace",
  "terminal.integrated.cursorStyle": "line",
  "terminal.integrated.cursorWidth": 2,
  "terminal.integrated.fontLigatures.enabled": true,

  // Formatting
  // Download the Prettier extension if you haven't already
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "prettier.singleQuote": true,
  "editor.formatOnSave": true, // this one is optional

  // Remove or comment out all other color customizations and follow Quantum theme :)
  "workbench.colorCustomizations": {},

  // Optional
  "editor.minimap.enabled": false,
  "workbench.panel.showLabels": false,
  "editor.padding.top": 20,
  "files.autoSave": "off",
  "editor.acceptSuggestionOnEnter": "off",
  "explorer.confirmDragAndDrop": false,
  "terminal.integrated.enableMultiLinePasteWarning": "never",
  "editor.quickSuggestions": {
    "strings": "inline"
  },
  // Additional settings for macOS
  "workbench.fontAliasing": "auto",
  "workbench.statusBar.feedback.visible": false
}
```

> Again, you can download and install the _Operator Mono Lig_ font for free from https://github.com/willfore/vscode_operator_mono_lig.

🧐 Please let me know if you've caught some kinda funky color, because this theme is new, and there are so many languages and VS Code parts that I don't use.

⭐ Don't forget to [star the repo](https://github.com/pandaproggit/quantum) to support me! Thanks 😁

### Enjoy! 😎
