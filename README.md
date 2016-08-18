# css-flex-align-self 0.0.7

Css module of single purpose classes for flex align self

#### Stats

272 | 28 | 28
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-flex-align-self
```

#### With Git

```
git clone https://github.com/tachyons-css/css-flex-align-self
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-flex-align-self";
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
<link rel="stylesheet" href="path/to/module/css/css-flex-align-self">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   FLEX ALIGN SELF
*/
.as-a { align-self: auto; }
.as-fs { align-self: flex-start; }
.as-fe { align-self: flex-end; }
.as-c { align-self: center; }
.as-b { align-self: baseline; }
.as-s { align-self: stretch; }
.as-i { align-self: inherit; }
@media screen and (min-width: 48em) {
 .as-a-ns { align-self: auto; }
 .as-fs-ns { align-self: flex-start; }
 .as-fe-ns { align-self: flex-end; }
 .as-c-ns { align-self: center; }
 .as-b-ns { align-self: baseline; }
 .as-s-ns { align-self: stretch; }
 .as-i-ns { align-self: inherit; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .as-a-m { align-self: auto; }
 .as-fs-m { align-self: flex-start; }
 .as-fe-m { align-self: flex-end; }
 .as-c-m { align-self: center; }
 .as-b-m { align-self: baseline; }
 .as-s-m { align-self: stretch; }
 .as-i-m { align-self: inherit; }
}
@media screen and (min-width: 64em) {
 .as-a-l { align-self: auto; }
 .as-fs-l { align-self: flex-start; }
 .as-fe-l { align-self: flex-end; }
 .as-c-l { align-self: center; }
 .as-b-l { align-self: baseline; }
 .as-s-l { align-self: stretch; }
 .as-i-l { align-self: inherit; }
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
