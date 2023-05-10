<h1 align="center">
  <a href="">
    <img src="apps/scalable/visual-studio-code.svg" alt="vscode" width="120" />
  </a>
  <br>
    Libadwaita
  <br></br>
</hi>

![libadwaita](libadwaita.png)

## Getting Started 

The "Custom CSS and JS Loader" extension is required to load custom CSS, and it might require additional configuration or permissions depending on your operating system. Please refer to the extension documentation for detailed instructions.

Upon successfully installing and configuring the "Custom CSS and JS Loader" extension, you can proceed with the subsequent steps to install the "vscode-libadwaita" workbench theme. Please follow the instructions outlined below:


1. Launch Visual Studio Code.
2. Select "Preferences: Open User Settings" to to modify the settings globally for all Visual Studio Code instance.
3. In the workspace or user settings, add the following configuration to enable custom CSS loading:

```json
"vscode_custom_css.imports": [
  "file:///home/username/libadwaita-vscode-theme/src/vs/workbench/browser/parts/editor/media/editorplaceholder.css",
  "file:///home/username/libadwaita-vscode-theme/src/vs/workbench/browser/parts/editor/media/tabstitlecontrol.css",
  "file:///home/username/libadwaita-vscode-theme/src/vs/workbench/contrib/interactiveEditor/browser/interactiveEditor.css",
  "file:///home/username/libadwaita-vscode-theme/src/miscellaneous.css"
]
```

## Credits

We would like to acknowledge any contributors to this repository and those who may contribute in the future. Their hard work and dedication have been essential to the development of this project. Additionally, we extend our appreciation to the GNOME community for their ongoing support and development of the original design guidelines upon which this repository is based. Without their efforts, this project would not have been possible.

## Bonus

If you're searching for an excellent theme to use with this, I strongly suggest taking a look at [vscode-adwaita](https://github.com/piousdeer/vscode-adwaita.git) made by [@piousdeer](https://github.com/piousdeer)! Alternatively, you can use the colorscheme provided in the repository. Please be aware, however, that it was customized to match my preferences and is therefore highly opinionated.

## License

This theme is distributed under the GNU General Public License v3.0. 
