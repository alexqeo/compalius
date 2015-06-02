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
$ cpalius style.(less|scss|styl)
```

For example, this command will compile new **style.css** file:

```bash
$ cpalius style.less
```

You can also name output file as you want:

```bash
$ cpalius style.less / my_styles.css
```

#### CoffeScript -> JS

```bash
$ cpalius scripts.coffee
```

```bash
$ cpalius scripts.coffee / my_scripts.js
```

#### Jade -> HTML

```bash
$ cpalius index.jade
```

```bash
$ cpalius index.jade / index.html
```

### Compile & Minify

To minify output file add the -min option in the end:

```bash
$ cpalius style.less -min
$ cpalius scripts.coffee -min

 or

$ cpalius style.less / my_styles.min.css -min
$ cpalius scripts.coffee / my_scripts.min.js -min
```