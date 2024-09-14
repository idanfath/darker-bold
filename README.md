# Darker Bold Theme

Welcome to the Darker Bold Theme! This theme enhances your coding experience with a bold and dark color scheme.

## Prerequisites

To get the best experience with this theme, please install the **CSS and JS Extension** for Visual Studio Code.

1. Open Visual Studio Code.
2. Go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window.
3. Search for `CSS and JS Extension`.
4. Click **Install**.

## Configuration

Move the **customcss** folder to your desired location. This folder contains the custom CSS and JS files for the Darker Bold Theme.

To fully integrate the Darker Bold Theme, please add the following configuration to your `settings.json` file:

```json
"vscode_custom_css.imports": [
    // path to custom css, for example:
    // "file:///c:/path/to/customcss/custom-vscode.css",
    // "file:///c:/path/to/customcss/vscode-script.js"
],
"window.title": "${activeEditorShort}${separator}${rootName}",
"window.titleSeparator": " | ",
"editor.semanticTokenColorCustomizations": {
    "enabled": true,
    "rules": {
        "method": {
            "fontStyle": "bold"
        },
        "function": {
            "fontStyle": "bold"
        },
        "parameter": {
            "fontStyle": "underline",
            "foreground": "#e8e8e8"
        },
        "class": {
            "fontStyle": "italic"
        },
    }
},
```

### How to Edit `settings.json`

1. Open Visual Studio Code.
2. Press `Ctrl + ,` to open the settings.
3. Click on the top right `{}` icon to open the `settings.json` file.
4. Copy and paste the above configuration into your `settings.json`.

Enjoy coding with the Darker Bold Theme!

## Feedback

If you have any feedback or issues, please open an issue on our [GitHub repository](https://github.com/idanfath/darker-bold).
