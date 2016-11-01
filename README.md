# css-flex-align-self 1.0.6

Css module of single purpose classes for flex align self

#### Stats

339 | 28 | 72
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-flex-align-self
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-flex-align-self
```

ssh:
```
git clone git@github.com:tachyons-css/css-flex-align-self.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-flex-align-self";
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
<link rel="stylesheet" href="http://unpkg.com/css-flex-align-self@1.0.6/css/css-flex-align-self.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-flex-align-self">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*
   FLEX ALIGN SELF
*/
.as-a { -ms-flex-item-align: auto; -ms-grid-row-align: auto; align-self: auto; }
.as-fs { -ms-flex-item-align: start; align-self: flex-start; }
.as-fe { -ms-flex-item-align: end; align-self: flex-end; }
.as-c { -ms-flex-item-align: center; -ms-grid-row-align: center; align-self: center; }
.as-b { -ms-flex-item-align: baseline; align-self: baseline; }
.as-s { -ms-flex-item-align: stretch; -ms-grid-row-align: stretch; align-self: stretch; }
.as-i { -ms-flex-item-align: inherit; -ms-grid-row-align: inherit; align-self: inherit; }
@media screen and (min-width: 48em) {
 .as-a-ns { -ms-flex-item-align: auto; -ms-grid-row-align: auto; align-self: auto; }
 .as-fs-ns { -ms-flex-item-align: start; align-self: flex-start; }
 .as-fe-ns { -ms-flex-item-align: end; align-self: flex-end; }
 .as-c-ns { -ms-flex-item-align: center; -ms-grid-row-align: center; align-self: center; }
 .as-b-ns { -ms-flex-item-align: baseline; align-self: baseline; }
 .as-s-ns { -ms-flex-item-align: stretch; -ms-grid-row-align: stretch; align-self: stretch; }
 .as-i-ns { -ms-flex-item-align: inherit; -ms-grid-row-align: inherit; align-self: inherit; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .as-a-m { -ms-flex-item-align: auto; -ms-grid-row-align: auto; align-self: auto; }
 .as-fs-m { -ms-flex-item-align: start; align-self: flex-start; }
 .as-fe-m { -ms-flex-item-align: end; align-self: flex-end; }
 .as-c-m { -ms-flex-item-align: center; -ms-grid-row-align: center; align-self: center; }
 .as-b-m { -ms-flex-item-align: baseline; align-self: baseline; }
 .as-s-m { -ms-flex-item-align: stretch; -ms-grid-row-align: stretch; align-self: stretch; }
 .as-i-m { -ms-flex-item-align: inherit; -ms-grid-row-align: inherit; align-self: inherit; }
}
@media screen and (min-width: 64em) {
 .as-a-l { -ms-flex-item-align: auto; -ms-grid-row-align: auto; align-self: auto; }
 .as-fs-l { -ms-flex-item-align: start; align-self: flex-start; }
 .as-fe-l { -ms-flex-item-align: end; align-self: flex-end; }
 .as-c-l { -ms-flex-item-align: center; -ms-grid-row-align: center; align-self: center; }
 .as-b-l { -ms-flex-item-align: baseline; align-self: baseline; }
 .as-s-l { -ms-flex-item-align: stretch; -ms-grid-row-align: stretch; align-self: stretch; }
 .as-i-l { -ms-flex-item-align: inherit; -ms-grid-row-align: inherit; align-self: inherit; }
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

