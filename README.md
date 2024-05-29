# Blossoms Dark Theme README

### Blossoms Dark Theme is a vibrant and eye-catching VS Code theme with a dark purple background and bright neon colors. This theme is designed to enhance your coding experience with its bold and distinct color scheme, making your code easy to read and aesthetically pleasing.

## Features

- **Dark Purple Background**: Provides a soothing base that reduces eye strain during long coding sessions.
- **Bright Neon Colors**: Highlights syntax elements in bright neon colors for better visibility and readability.
- **Consistent Design**: Ensures a cohesive and professional look across various programming languages and file types.
- **Jinja Support**: Includes syntax highlighting for Jinja templates when a Jinja syntax extension is enabled.


## Screenshots

### JavaScript
![JavaScript Example](imgs/js.png)

### HTML
![HTML Example](imgs/html.png)

### Python
![Python Example](imgs/python.png)

## Installation

1. Open **Extensions** sidebar panel in VS Code. `View → Extensions`
2. Search for `Dark Purple Neon Theme`
3. Click **Install** to install it
4. Click **Reload** to reload your editor
5. Code > Preferences > Color Theme > **Dark Purple Neon Theme**

## Usage

After installation, you can easily switch to the Dark Purple Neon theme by going to the Command Palette (`Ctrl+Shift+P`), typing `Preferences: Color Theme`, and selecting **Dark Purple Neon Theme** from the list.

## Jinja Support

For Jinja template support, make sure to install a Jinja syntax extension such as [Jinja](https://marketplace.visualstudio.com/items?itemName=wholroyd.jinja).


## Customization

If you would like to customize the theme to better suit your preferences, you can modify your settings in the `settings.json` file:

```json
"workbench.colorCustomizations": {
  "editor.background": "#1e1e1e",
  "editor.foreground": "#d4d4d4"
},
"editor.tokenColorCustomizations": {
  "textMateRules": [
    {
      "scope": "comment",
      "settings": {
        "foreground": "#6a9955"
      }
    }
    // Add more customizations here...
  ]
}