# QUANTUM THEME FOR VSCODE!

🎨 The best blue, lime, yellow, purple and cyan color comboed theme!

![Preview](https://github.com/calebephrem/quantum/blob/main/assets/preview.png?raw=true)

## 🎨 The Theme

- 🌌 The **Quantum** theme family includes two core variants: **Quantum** and **Quantum Dark**. Both are dark themes, but **Quantum Dark** takes it a step further with deeper contrast and a more subdued palette.

- 🧱 Prefer a bit more structure? Try the bordered editions: **Quantum Bordered** and **Quantum Dark Bordered**. These add semi-transparent borders to panels and editors for a subtle, organized feel.

- 🚫 Not a fan of italic fonts? No problem. The **Non-Italicized** variants—**Quantum Non-Italicized** and **Quantum Dark Non-Italicized**—keep everything upright and crisp, perfect for a cleaner coding experience.

- 🧠 Generally, Quantum theme provides:

<table>
  <thead>
    <tr>
      <th>🌟 Theme</th>
      <th>📝 Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Quantum</strong></td>
      <td>⚡ The original. Default, preferred, legendary. A balanced blend of vibrance and clarity.</td>
    </tr>
    <tr>
      <td><strong>Quantum Dark</strong></td>
      <td>🌑 A deeper dive into Quantum—same vibe, darker tones. Ideal for night owls and moody coders.</td>
    </tr>
    <tr>
      <td><strong>Quantum Bordered</strong></td>
      <td>🧱 Quantum with a twist—adds subtle borders for enhanced visual structure.</td>
    </tr>
    <tr>
      <td><strong>Quantum Dark Bordered</strong></td>
      <td>🕶️ Combines the depth of Quantum Dark with the crispness of borders. Sleek and structured.</td>
    </tr>
    <tr>
      <td><strong>Quantum Non-Italicized</strong></td>
      <td>🚫 <em>No slants allowed.</em> A clean-cut version of Quantum for those who prefer upright fonts.</td>
    </tr>
    <tr>
      <td><strong>Quantum Dark Non-Italicized</strong></td>
      <td>🌘 The bold, italic-free sibling of Quantum Dark. Minimalist and moody.</td>
    </tr>
  </tbody>
</table>

## ⬇️ Installation

1. Open Extensions by clicking on the extension icon on the left sidebar panel in your VS Code
2. Search **Quantum**
3. Install the one by _Caleb Ephrem_
4. Press `ctrl+shift+P` to expand the command palette (`cmd+shift+P` on mac)
5. Go under `Preferences: Color Theme`
6. Search **Quantum**
7. Then click on **Quantum** (or other variants of it)
8. Give the [repo](https://github.com/calebephrem/quantum) a ⭐star

🔥 Walla! You have the Quantum theme activated! ⚡

## ⚙️ Recommended Settings

### ✨ Recommended Settings for Maximum Quantum Vibes

Want to make Quantum look even better? These are some hand-picked tweaks to elevate your workspace aesthetics.

🛠️ To apply them:

1. Open your command palette (`Ctrl+Shift+P`)
2. Search for `Preferences: Open User Settings (JSON)`
3. Edit the recommended settings into your `settings.json` file

💡 **Optional settings** are just that—optional! Feel free to skip them if they’re not your style. They add a little extra flair, but nothing critical 🙃

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
  // Additional settings for macOS
  "workbench.fontAliasing": "auto",
  "workbench.statusBar.feedback.visible": false
}
```

> Again, you can download and install the _Operator Mono Lig_ font for free from https://github.com/willfore/vscode_operator_mono_lig.

## 📷 Screenshots

### CSS + SCSS

![css+scss](https://github.com/calebephrem/quantum/blob/main/assets/screenshots/css-scss.png?raw=true)

### Nodejs + mongodb

![node+mongo](https://github.com/calebephrem/quantum/blob/main/assets/screenshots/node-mongo.png?raw=true)

### Python + React

![python+react](https://github.com/calebephrem/quantum/blob/main/assets/screenshots/python-react.png?raw=true)

### HTML + Markdown

![html+markdown](https://github.com/calebephrem/quantum/blob/main/assets/screenshots/html-markdown.png?raw=true)

---

### 📄 License

Quantum is MIT-based with extra restrictions:

- No selling
- No removing the license or claiming authorship

See the full [LICENSE](./LICENSE) for details.

### 🚀 Final Notes

🧐 If you spot any funky colors or odd styling quirks—especially in languages or VS Code areas I haven’t tested—please don’t hesitate to [open an issue](https://github.com/calebephrem/quantum/issues). Quantum is still fresh, and your feedback helps it grow stronger!

🌟 If you’re enjoying the theme, show some love with:

- ⭐ Giving the [repo](https://github.com/calebephrem/quantum) a star
- ✨ Rating it 5 stars on the [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=CalebEphrem.quantum)
- 💬 Drop a review if you feel inspired!

Thanks a ton for the support 😁

### Enjoy coding! 😎
