[![GitHub](https://img.shields.io/github/issues/mohamednajiub/wp-workflow?style=flat-square)](https://github.com/mohamednajiub/wp-workflow/issues/) [![GitHub](https://img.shields.io/github/forks/mohamednajiub/wp-workflow?style=social)](https://github.com/mohamednajiub/wp-workflow/network/members) [![GitHub](https://img.shields.io/github/license/mohamednajiub/wp-workflow?style=flat-square)](https://github.com/mohamednajiub/wp-workflow/blob/master/LICENSE)

# WP-Workflow

WP Workflow is a powerful Gulp workflow for making Developing WordPress themes easier and productivity ⌛.

## How to use

- for development:\
  1- `npm install wp-workflow -g`\
  2- go to you wp project directory\
  3- run `wp-workflow`\
  4- wait untill installing project and answer prompt questions\
  5- run `npm start` and then start development.

- for production\
  1- Go to your theme directory.\
  2- run `npm run build`.

## WP-Workflow Capabilities

What WP-workflow can do?

### CSS Features

- convert sass to css.
- add auto prefixes to css for last 5 versions of browsers.
- create .map file for css if you are on development mode.
- minify css files when running build and remove .map files.

### JS Features

- convert ES6 to ES5.
- create .map file for JS if you are on development mode.
- minify js files when running build and remove .map files.
- remove console.log and debuggers from JS if you are in production mode.

### Images Features

- compress static images.
- move compressed static images from src folder to images folder in dest.

### Live Server Features

- open live server after finish all basic tasks "styles, scripts, images".
- reload server if there is changes in any files or folder.

### Create compressed file

wp-workflow can compress your theme files and folders that you can publish it directly after finishing development

- `npm run build`.
- wait to finish bundling files
- you will be asked for if you want zip file or not choose yes.
- the compressed file will be created in project root.

### Project folder structure

```
localhost
├── wordpress project
│   └── wp-content
│       ├── themes
│       │   ├── theme name
│       │   │   ├── dest
│       │   │   │   ├── css
│       │   │   │   │   └── compiled css files
│       │   │   │   └── js
│       │   │   │   |    └── compiled js files
│       │   │   │   └── images
│       │   │   │        └── compiled images
│       │   │   ├── src
│       │   │   │   ├── sass
│       │   │   │   │   └── main.scss
│       │   │   │   └── scripts
│       │   │   │   |    └── main.js
│       │   │   │   └── images
│       │   │   │   |    └── image.png
│       │   |   |── inc
│       │   │   │   ├── php files
│       │   |   ├── templates-parts
│       │   |   │   └── php files
│       │   |   └── wp templates
│       └── index.php
```
