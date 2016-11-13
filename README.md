# Maestro Framework
<p align="center"><img style="margin-bottom:3em;" width="150"src="http://images.all-free-download.com/images/graphicthumb/maestro_logo2_29719.jpg"> 
<br> <br>
[![Packagist](https://img.shields.io/packagist/l/doctrine/orm.svg?style=flat-square)]()</p> <br>
Maestro is a powerful CSS Framework made in France. It is modern, responsive-design and easy to use. Therefore it will be perfect for your web projects.

## Installation
### 1. Quick start
Run one of these commands :
```
$ git clone git@github.com:xchopin/Maestro.git
```
```
$ bower install maestro
```

### 2. Link the css file to your HTML page
```
 <link rel="stylesheet" href="css/style.min.css">
```

## Settings

### 1. Before editing
```
 $ cd yourProject/ 
 $ sass --watch sass:css --style compressed
```
### 2. _variable.scss
File containing every global variables (font,size,color,...)

### 3. presets/_function.scss
Useful file containing some functions such as transitions or shadow effects

### 4. presets/*.scss
Files containing mixins and other place holders.


## What's included

Within the download you'll find the following directories and files, logically grouping common assets and providing both compiled and minified variations. You'll see something like this:

```
maestro/
├── css/
│   └── style.css
├── ressources/
│   ├── background.png
│   ├── css.png
│   ├── html.png
│   ├── maestro.ttf
│   ├── sass.png
└── sass/
    ├── presets/
    │   ├──_alerte.scss
    │   ├──_bouton.scss
    │   ├──_composant.scss
    │   ├──_conteneur.scss
    │   ├──_fonction.scss
    │   ├──_grille.scss
    │   ├──_input.scss
    │   ├──_navbar.scss
    │   └──_typographie.scss
    ├──_bouton.scss
    ├──_composant.scss
    ├──_demo.scss
    ├──_grille.scss
    ├──_input.scss
    ├──_reset.scss
    ├──_tableau.scss
    ├──_typographie.scss
    ├──_variables.scss
    └──style.scss
```
## License

The Maestro framework is open-sourced software licensed under the MIT license.
