# Compalius

Simple script to compile all famous web preprocessors formats

[![npm version](https://badge.fury.io/js/compalius.svg)](https://www.npmjs.com/package/compalius)

## Getting Started

Install package:

```bash
$ npm install -g compalius
```

## Usage

### Compile

#### Less, Sass, Stylus -> CSS

```bash
$ cpalius styles.(less|scss|styl)
```

For example, this command will compile new **styles.css** file:

```bash
$ cpalius styles.less
```

You can also name output file as you want:

```bash
$ cpalius styles.less / my_styles.css
```

#### CoffeScript -> JS

```bash
$ cpalius scripts.coffee
$ cpalius scripts.coffee / my_scripts.js
```

#### Jade -> HTML

```bash
$ cpalius index.jade
$ cpalius index.jade / index.html
```

### Compile & Minify

To minify output file add the -min option in the end:

```bash
$ cpalius styles.less -min
$ cpalius scripts.coffee -min

 or

$ cpalius styles.less / my_styles.min.css -min
$ cpalius scripts.coffee / my_scripts.min.js -min
```