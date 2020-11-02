# Electron React Boilerplate icons generator

it was panful to generate all icons for [Electron-React-Boilerplate](https://github.com/electron-react-boilerplate/electron-react-boilerplate) each time there are changes in the icon. So i created this package to generate all icons from single icon.png in the resources directory of  [Electron-React-Boilerplate](https://github.com/electron-react-boilerplate/electron-react-boilerplate)

### Usage with electron react boilerplate

###### Installation

```bash
npm install --save-dev erb-icons-gen@latest
# or 
yarn add -D erb-icons-gen@latest
```

###### Add  the following script to `package.json` file

```json
"scripts": {
    "gen:icons" : "erb-generate --input resources/icon.png --output resources/"
}
```

###### Generate all icons from single icon.png

make sure that you have icon.png in your `resources` directory and run the following command in your project root.

```bash
npm run gen:icons
# or
yarn gen:icons
```


