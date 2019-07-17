## :page_facing_up: Used technologies

<br/>
<br/>

![header](../assets/header.png?raw=true)

<br/>
<br/>
<br/>

## :iphone: View Site

:link: [link](https://devmeed.com/supreme/)
<p align="center">
<img src="../assets/imac.png?raw=true" width="620" />
<img src="../assets/ipad.png?raw=true" width="350" style="padding-left:2px"/> 
<img src="../assets/iphone.png?raw=true" width="200" style="padding-left:25px"/>
</p>

<br/>
<br/>
<br/>

## :department_store: Project Structure

<br/>

```
├── dist/                          # Static version of the website
│   ├── css/                       # Folder for concatenated css files
│   ├── fonts/                     # All fonts files
│   ├── img/                       # Images
│   ├── about.html                 # Company information
│   ├── index.html                 # Main page
│   ├── products.html              # Available products with description
│   └── store.html                 # Contacts information
├── src/                           # Source files
│   ├── fonts/                     # Fonts
│   │   └── fonts.list             # Google Fonts config
│   ├── img/                       # Site images
│   ├── js/                        # Javascript files
│   │   ├── bootstrap.js           # Enable/disable required modules
│   │   ├── entry.js               # Webpack entry point
│   │   └── main.js                # All user scripts
│   ├── styles/                    # Styles
│   │   ├── bootstrap/             # Bootstrap sass config
│   │   │   ├── bootstrap.scss     # Enable/disable required modules
│   │   │   └── _variables.scss    # Core setting
│   │   └── main.styl              # Main stylesheet file
│   ├── templates/                 # Site templates (Pug)
│   │   ├── pages/                 # Pug only looks for this dir
│   │   │   ├── about.pug          # Company information template
│   │   │   ├── index.pug          # Main page template
│   │   │   ├── products.pug       # Available products with description template
│   │   │   └── store.pug          # Contacts information template
│   │   ├── footer.pug             # Site footer
│   │   ├── header.pug             # Site header
│   │   ├── layout.pug             # Main layout
│   │   └── navigation.pug         # Site navigation
│   └── vendor/                    # Appears if CUSTOM_SOURCE options specified or fonts enabled.
│       ├── bootstrap/             # Bootstrap source for editing
│       └── googleFonts/           # Storage for downloaded fonts
├── tmp/                           # Temporary folder
│   └── manifest/                  # Manifests for the production build
│       └── rev-images.json        # Hashed images names
├── .babelrc                       # Babel presets for latest js features
├── .eslintrc.js                   # ESLint config
├── .gitignore                     # List of files ignored by git
├── .prettierrc                    # Prettier formatter config
├── license                        # Project license
├── readme.md                      # Description of the project
├── gulpfile.babel.js              # Gulpfile config and tasks
└── package.json                   # Node.js dependencies and scripts
```
