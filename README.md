# Compalius

Simple shell-compiler to convert .less .styl .scss files into .css

[![npm version](https://badge.fury.io/js/compalius.svg)](https://www.npmjs.com/package/compalius)

## Getting Started

Install package:

```bash
$ npm install -g compalius
```

## Usage

### Compile

Compile file into CSS:

```bash
$ cpalius style.(less|scss|styl)
```

For example, this command will compile new style.css file:

```bash
$ cpalius style.less
```

You can also name output file as you want:

```bash
$ cpalius style.less / my_styles.css
```

### Compile & Minify

To minify output file add the -min option in the end:

```bash
$ cpalius style.less -min

 or

$ cpalius style.less / my_styles.css -min
```