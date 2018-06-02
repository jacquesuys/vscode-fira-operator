# vscode-fira-operator

![alt text](./example.png 'Screenshot')

The Fira Code and Operator Mono combo. It uses the [Atom One Dark Theme](https://github.com/atom/one-dark-syntax) (default theme for Atom).
Install the following extensions: [Atom One Dark Theme](https://github.com/atom/one-dark-syntax) and [Custom CSS and JS Loader](https://github.com/be5invis/vscode-custom-css/).
Add the fonts supplied in the folder to your OS's font management.
**(Be sure to follow the instructions inside the Custom CSS README)**

### vs_custom.css

By clicking on the vscode_custom_css.imports array url, it might prompt you to create file, proceed and paste the supplied CSS inside.

```
/* Keywords, decorators, comments */
.mtk5,
.mtk11,
.mtk15 {
  /* For Mac */
  font-family: "OperatorMono-BookItalic";

  /* For Windows
    font-family: "Operator Mono";
    font-style: italic;
  */

  /* For Linux
    font-family: Operator Mono Medium;
    font-style: italic;
    font-size: 17px;
  */
}
```

### Update VSCode

Press **_ctrl + shift + P_** and **_Reload Custom CSS and JS_**

### User Settings (VS Code)

```
// Place your settings in this file to overwrite the default settings
{
  "window.zoomLevel": 0,
  "editor.fontSize": 17,
  "editor.fontFamily": "Fira Code",
  "editor.fontWeight": "normal",
  "editor.fontLigatures": true,
  "editor.tabCompletion": true,
  "editor.tabSize": 2,
  "vsicons.projectDetection.autoReload": true,
  "editor.minimap.enabled": false,
  "workbench.iconTheme": "vscode-icons",
  "files.autoSave": "off",
  "editor.formatOnSave": true,
  "workbench.colorTheme": "Atom One Dark",
  "vscode_custom_css.policy": true,
  "vscode_custom_css.imports": [
    ""
  ]
}
```

### Custom setup

Depending on your theme, you might want to choose which parts of the syntax is cursive or not.
You can alter the above CSS file and add the classes that your syntax needs by inspecting them inside the developer tools shipped with VS Code. **(Help > Toggle Developer Tools)**
