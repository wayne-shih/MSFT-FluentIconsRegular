# Microsoft – Fluent System Icons

![collage of fluent system icons](docs/fluentsystemicons.svg)

### Intro

This repository contains a fork of Fluent System Icons [`src/figma`](src/figma) and exported svg from the figma file [`src/icons`](src/icons). Utilizing an export/render tool designed for [Codicons](https://github.com/microsoft/vscode-codicons), a ttf font file is created in [`dist`](dist), but more importantly an easy searchable web portal is generated. 

## Tool 

This tool takes the Fluent System icons and converts them into an font using the [icon-font-generator](https://github.com/Workshape/icon-font-generator). All icons are stored under `src > icons`. ~~The mappings of the class names and unicode characters are stored in `src/template/mapping.json`~~ as well as the default styles under `src/template/styles.hbs`.

### Install

```
npm install
```

### Build

```
npm run dev
```

Output will be exported to a `dist` folder. 

### Update Packages

You can run `npm outdated` to see if there are any package updates. To update packages, run:

```
npm update
```

### Add Icons

Simply export your icons (svg) to the `src/icons` folder and run the the build command. The build command will also remove any subfolders in the `icons` folder to keep the folder structure consistent.

## License

Fluent System Icons are made by Microsoft Corporation licensed under [Creative Commons Attribution 4.0 International Public License](https://creativecommons.org/licenses/by/4.0/legalcode). Original file can be found at https://www.figma.com/community/file/836835755999342788 

All other code in the repository is a modified version of [@microsoft/vscode-codicons](https://github.com/microsoft/vscode-codicons/tree/834f35ab47a04cf60eb5a51b1c2dab791d2d576c) licensed under the [MIT License](https://opensource.org/licenses/MIT), see the
[LICENSE-CODE](LICENSE-CODE) file.
