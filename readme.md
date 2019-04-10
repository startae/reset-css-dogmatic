# reset.css

A **modified and dogmatic** version of Eric Meyer's [CSS reset](https://meyerweb.com/eric/tools/css/reset/). PostCSS, webpack, Sass, and Less friendly.

## Install

With curl:

```command
$ curl -O "https://unpkg.com/reset-css-dogmatic@1.0.4/reset.css"
$ curl -O "https://unpkg.com/reset-css-dogmatic@1.0.4/sass/_reset.scss"
$ curl -O "https://unpkg.com/reset-css-dogmatic@1.0.4/less/reset.less"
```

With [NPM](http://npmjs.com):

```command
$ npm install --save reset-css-dogmatic
```

With [Yarn](https://yarnpkg.com):

```command
$ yarn add reset-css-dogmatic
```

With [Bower](http://bower.io):

```command
$ bower install reset-css-dogmatic
```

## Usage

HTML:

```html
<link rel="stylesheet" href="/path/to/reset-css-dogmatic/reset.css" />
```

CSS:

```css
@import '/path/to/reset-css-dogmatic/reset.css';
```

Via PostCSS and [postcss-import](https://github.com/postcss/postcss-import):

```css
@import 'reset-css-dogmatic';
```

Via webpack and [css-loader](https://github.com/webpack-contrib/css-loader):

```js
import 'reset-css-dogmatic';
```

Via Sass:

```scss
@import '/path/to/reset-css-dogmatic/sass/reset';
```

Via Less:

```less
@import '/path/to/reset-css-dogmatic/less/reset';
```