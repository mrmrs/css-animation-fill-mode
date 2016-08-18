# css-animation-fill-mode 0.0.7

Css module of single purpose classes for animation fill mode

#### Stats

223 | 16 | 16
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-animation-fill-mode
```

#### With Git

```
git clone https://github.com/tachyons-css/css-animation-fill-mode
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-animation-fill-mode";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-animation-fill-mode">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   ANIMATION FILL MODE
*/
.a-fil-non { animation-fill-mode: none; }
.a-fil-frw { animation-fill-mode: forwards; }
.a-fil-bck { animation-fill-mode: backwards; }
.a-fil-bth { animation-fill-mode: both; }
@media screen and (min-width: 48em) {
 .a-fil-non-ns { animation-fill-mode: none; }
 .a-fil-frw-ns { animation-fill-mode: forwards; }
 .a-fil-bck-ns { animation-fill-mode: backwards; }
 .a-fil-bth-ns { animation-fill-mode: both; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .a-fil-non-m { animation-fill-mode: none; }
 .a-fil-frw-m { animation-fill-mode: forwards; }
 .a-fil-bck-m { animation-fill-mode: backwards; }
 .a-fil-bth-m { animation-fill-mode: both; }
}
@media screen and (min-width: 64em) {
 .a-fil-non-l { animation-fill-mode: none; }
 .a-fil-frw-l { animation-fill-mode: forwards; }
 .a-fil-bck-l { animation-fill-mode: backwards; }
 .a-fil-bth-l { animation-fill-mode: both; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

ISC
