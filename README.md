# Chunin HTML Reporter

_Chūnin HTML_ is a part of
[Chūnin Core](https://github.com/Chunin-Org/chunin-core) and
[Chūnin Extension]() that parse `report.chunin` files and generate
pretty HTML reports.

## MVP

* Looking for chunin.toml file (or any other config file, based on
  extension language) and declaring generation type
* Support for two generation types
  * On flight generation (Only `index.html` file created, all other
    files rendering on flight)
  * Static generation (On first `index.html` opening all other html
    files will be generated and pre-filed with code)
* All Vue code must be compiled into three files, and that files must be
  released as a new version of `chunin-html`:
  * index.html
  * styles.css
  * main.js
* Chūnin-html must be easy accessible from any extension or core and
  included in their releases

## Project setup

```
npm install
```

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

### Run your unit tests

```
npm run test:unit
```

### Lints and fixes files

```
npm run lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).
