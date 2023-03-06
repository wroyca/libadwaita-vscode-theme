# Libadwaita theme for Visual Studio Code.

If you're keen on using this theme, I suggest forking it and customizing it according to your preferences to make it a perfect fit. However, in case you make any modifications or enhancements to the theme, I would be more than happy to review and merge your pull request. Thank you for considering this theme! 🎉

![libadwaita](libadwaita.png)

## Installation

1. First, clone the project.

2. Next, you will need to install the [Custom CSS and JS Loader](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css) extension from Visual Studio Code Marketplace. Be sure to carefully follow the instructions provided with the extension, so that VS Code can patch itself properly.

3. Finally, open your VS Code settings.json file and add the following lines. Remember to replace file:///home/username/vscode-libadwaita with the full path to the directory where you cloned the project:

```
{
  "window.menuBarVisibility": "toggle",
  "vscode_custom_css.imports": [
    "file:///home/username/vscode-libadwaita/src/vs/workbench/browser/parts/editor/media/tabstitlecontrol.css",
    "file:///home/username/vscode-libadwaita/src/vs/editor/browser/viewParts/viewCursors/viewCursors.css",
    "file:///home/username/vscode-libadwaita/src/vs/editor/contrib/bracketMatching/browser/bracketMatching.css",
    "file:///home/username/vscode-libadwaita/src/vs/editor/browser/viewParts/minimap/minimap.css",
    "file:///home/username/vscode-libadwaita/src/vs/editor/contrib/wordHighlighter/browser/highlightDecorations.css",
    "file:///home/username/vscode-libadwaita/src/vs/editor/contrib/hover/browser/hover.css",
    "file:///home/username/vscode-libadwaita/src/vs/editor/contrib/suggest/browser/media/suggest.css",
    "file:///home/username/vscode-libadwaita/src/vs/editor/contrib/parameterHints/browser/parameterHints.css",
    "file:///home/username/vscode-libadwaita/src/vs/platform/quickinput/browser/media/quickInput.css",
    "file:///home/username/vscode-libadwaita/src/vs/base/browser/ui/scrollbar/media/scrollbars.css",
    "file:///home/username/vscode-libadwaita/src/vs/base/browser/ui/list/list.css"
  ]
}
```

## Bonus

If you're searching for an excellent theme to use with this, I strongly suggest taking a look at [vscode-adwaita](https://github.com/piousdeer/vscode-adwaita.git). It's an incredible creation by [@piousdeer](https://github.com/piousdeer)! :) Alternatively, you can use the colorscheme provided in the repository. Please be aware, however, that it was customized to match my preferences and is therefore highly opinionated.
