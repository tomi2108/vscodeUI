STEPS:

1.
Enable CSS `:has()` support via the experimental features flag

`code --enable-experimental-web-platform-features`

Append this flag in the vscode shortcut properties to avoid passing it every time.

2.
Install [Custom CSS Loader](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css) extension and enable it.


3.
Add these in your settings.json file:

```json
"editor.suggestLineHeight": 28,
"workbench.colorCustomizations": {
  "settings.sashBorder": "#181a1f",
  "scrollbar.shadow": "#ff000000",
  "focusBorder": "#ff000000"
},
```

Thank you.

