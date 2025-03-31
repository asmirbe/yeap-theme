<div align="center">
  <img src="https://raw.githubusercontent.com/asmirbe/yeap-theme/refs/heads/master/media/small.png" width="120" alt="Yeap Theme Logo" />
  <h1 align="center">Yeap Theme</h1>
  <p align="center">An official Yeap theme for Visual Studio Code.</p>
</div>
<p align="center">
  <img src="./media/preview.png" alt="Theme preview in Visual Studio Code" />
</p>

## Install

Download the **`.vsix`** theme from the [Releases](https://github.com/asmirbe/yeap-theme/releases/tag/v1.0.5) section and drag it into the Extensions panel in VS Code.

## Recommendations

Below you can find a few recommendations for your `settings.json` to match the Yeap experience even closer in your Visual Studio Code:

```JSON
{
  // Editor
  "editor.smoothScrolling": true,
  "editor.fontSize": 14,
  "editor.fontFamily": "'Fira Code'",
  "editor.mouseWheelZoom": false,
  "editor.fontLigatures": true,
  "editor.minimap.size": "proportional",
  "editor.cursorBlinking": "expand",
  "editor.cursorSmoothCaretAnimation": "on",
  "window.titleBarStyle": "custom",
  // Terminal
  "terminal.integrated.mouseWheelZoom": false,
  "terminal.integrated.cursorStyle": "line",
  "terminal.integrated.cursorBlinking": true,
  // As you like
  "breadcrumbs.enabled": false,
  "editor.minimap.enabled": false
}
```

> You can download the [Fira Code font][fira-code-install] from GitHub.

[fira-code-install]: https://github.com/tonsky/FiraCode
