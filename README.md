# Compalius

Simple shell-compiler to convert .less .styl .scss files into .css

## Getting Started

Install package:

```bash
$ npm install -g compalius
```

## Usage

Compile file into css:

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