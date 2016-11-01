# css-animation-fill-mode 1.0.7

Css module of single purpose classes for animation fill mode

#### Stats

254 | 16 | 32
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-animation-fill-mode
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-animation-fill-mode
```

ssh:
```
git clone git@github.com:tachyons-css/css-animation-fill-mode.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-animation-fill-mode";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/css-animation-fill-mode@1.0.7/css/css-animation-fill-mode.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-animation-fill-mode">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*
   ANIMATION FILL MODE
*/
.a-fil-non { -webkit-animation-fill-mode: none; animation-fill-mode: none; }
.a-fil-frw { -webkit-animation-fill-mode: forwards; animation-fill-mode: forwards; }
.a-fil-bck { -webkit-animation-fill-mode: backwards; animation-fill-mode: backwards; }
.a-fil-bth { -webkit-animation-fill-mode: both; animation-fill-mode: both; }
@media screen and (min-width: 48em) {
 .a-fil-non-ns { -webkit-animation-fill-mode: none; animation-fill-mode: none; }
 .a-fil-frw-ns { -webkit-animation-fill-mode: forwards; animation-fill-mode: forwards; }
 .a-fil-bck-ns { -webkit-animation-fill-mode: backwards; animation-fill-mode: backwards; }
 .a-fil-bth-ns { -webkit-animation-fill-mode: both; animation-fill-mode: both; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .a-fil-non-m { -webkit-animation-fill-mode: none; animation-fill-mode: none; }
 .a-fil-frw-m { -webkit-animation-fill-mode: forwards; animation-fill-mode: forwards; }
 .a-fil-bck-m { -webkit-animation-fill-mode: backwards; animation-fill-mode: backwards; }
 .a-fil-bth-m { -webkit-animation-fill-mode: both; animation-fill-mode: both; }
}
@media screen and (min-width: 64em) {
 .a-fil-non-l { -webkit-animation-fill-mode: none; animation-fill-mode: none; }
 .a-fil-frw-l { -webkit-animation-fill-mode: forwards; animation-fill-mode: forwards; }
 .a-fil-bck-l { -webkit-animation-fill-mode: backwards; animation-fill-mode: backwards; }
 .a-fil-bth-l { -webkit-animation-fill-mode: both; animation-fill-mode: both; }
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

