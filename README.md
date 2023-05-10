<h1 align="center">
  <a href="">
    <img src="apps/scalable/visual-studio-code.svg" alt="vscode" width="120" />
  </a>
  <br>
    Libadwaita
  <br>
</hi>


## Getting Started 

The "Custom CSS and JS Loader" extension is required to load custom CSS, and it might require additional configuration or permissions depending on your operating system. Please refer to the extension documentation for detailed instructions.

Upon successfully installing and configuring the "Custom CSS and JS Loader" extension, you can proceed with the subsequent steps to install the "vscode-libadwaita" workbench theme. Please follow the instructions outlined below:


1. Launch Visual Studio Code.
2. Open the **Extensions** view by clicking on the square icon in the sidebar or by using the shortcut `Ctrl+Shift+X`.
3. Search for and install the **Custom CSS and JS Loader** extension by **be5invis**.
4. Once installed, open the **Command Palette** by pressing `Ctrl+Shift+P`.
5. Select "Preferences: Open Workspace Settings" to open the workspace settings for your project.
   - Alternatively, you can select "Preferences: Open User Settings" to modify the settings globally for all Visual Studio Code instance.
6. In the workspace or user settings, add the following configuration to enable custom CSS loading:

```json
"vscode_custom_css.imports": [
  "file:///home/username/vscode-libadwaita/src/**/*.css"
]
```

## Credits

We would like to acknowledge any contributors to this repository and those who may contribute in the future. Their hard work and dedication have been essential to the development of this project. Additionally, we extend our appreciation to the GNOME community for their ongoing support and development of the original design guidelines upon which this repository is based. Without their efforts, this project would not have been possible.

## License

This theme is distributed under the GNU General Public License v3.0. 