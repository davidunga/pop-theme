<p align="center">
  <img src="https://github.com/davidunga/pop-theme/blob/main/meta-assests/banner-001.png" width="250" />
</p>
<p align="center">
A crisp theme that keeps you in flow. Probably compatible with your favorite editor.
</p>

## 🔧 Installation

### 🔷 VS Code

1. **Install `vsce`** (if not already installed):

   - **macOS**:
     ```bash
     brew install vsce
     ```
   - **Linux / Windows (via Node.js)**:
     ```bash
     npm install -g vsce
     ```

2. **Build and install the theme**:
   ```bash
   cd pop-theme/vs-code
   vsce package
   code --install-extension darkpop-*.vsix
   ```

3. **Activate**:
   - Open Command Palette → `Color Theme` → Select **DarkPop**

> 💡 On **Windows**, make sure `code` is available in PATH: `Ctrl+Shift+P` → `Shell Command: Install 'code' command`.

---

### 🅂 Sublime Text

1. Open `Preferences` → `Browse Packages…`
2. Create a folder named `DarkPop` and place `DarkPop.tmTheme` inside.

- **macOS default**: `~/Library/Application Support/Sublime Text/Packages/DarkPop/`
- **Linux default**: `~/.config/sublime-text/Packages/DarkPop/`
- **Windows default**: `%APPDATA%\Sublime Text\Packages\DarkPop\`

3. Activate via `Preferences` → `Color Scheme` → Select **DarkPop**

---

### 🌸 TextMate

1. Copy `DarkPop.tmTheme` to the themes folder:

- **macOS default**: `~/Library/Application Support/TextMate/Themes/`
- **Linux default**: `~/.textmate/Themes/`

```bash
cp textmate/DarkPop.tmTheme <theme-folder>
```

2. Restart TextMate.
3. Go to `Preferences` → `Fonts & Colors` → Choose **DarkPop**

---

### 🧠 JetBrains IDEs

1. Go to `Preferences` → `Editor` → `TextMate Bundles`
2. Click `+` and select the `textmate/` folder from this repo
3. Apply and choose **DarkPop** from your color schemes

---

### 💠 Zed

1. Copy `DarkPop.tmTheme` into Zed’s theme folder:

- **Linux/macOS default**: `~/.config/zed/themes/`
- **Windows default**: `C:\Users\<User>\AppData\Roaming\zed\themes\`

```bash
cp textmate/DarkPop.tmTheme <zed-theme-folder>
```

2. Restart Zed.
3. Open Command Palette → Select **DarkPop**

---

### 🧾 CotEditor

1. Open CotEditor
2. Go to `CotEditor` → `Settings` → `Appearance` → `Color Themes`
3. Click the ⚙️ (gear icon) → `Import`
4. Select `DarkPop.tmTheme` from the `textmate` folder from this repo
5. Choose **DarkPop** from the theme selector

---

### 🛠️ Other Editors

Any editor that supports **TextMate themes** (`.tmTheme`) can use **DarkPop**.
Check your editor’s documentation to locate its themes directory and how to activate custom color schemes.

---
