# CSS FLEX ALIGN SELF

  Mobile-first classes for css-flex-align-self.
  Set the desired css-flex-align-self on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-flex-align-self
```
View on [npm](https://www.npmjs.org/package/css-flex-align-self)


## File Size

1.1K flex-align-self.css
895B flex-align-self.min.css
227B minified and gzipped

## The Code
```
.as-a {  align-self: auto; }
.as-fs { align-self: flex-start; }
.as-fe { align-self: flex-end; }
.as-c {  align-self: center; }
.as-b {  align-self: baseline; }
.as-s {  align-self: stretch; }
.as-i {  align-self: inherit; }

@media screen and (min-width: 48em) {
  .as-a-ns {  align-self: auto; }
  .as-fs-ns { align-self: flex-start; }
  .as-fe-ns { align-self: flex-end; }
  .as-c-ns {  align-self: center; }
  .as-b-ns {  align-self: baseline; }
  .as-s-ns {  align-self: stretch; }
  .as-i-ns {  align-self: inherit; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .as-a-m {  align-self: auto; }
  .as-fs-m { align-self: flex-start; }
  .as-fe-m { align-self: flex-end; }
  .as-c-m {  align-self: center; }
  .as-b-m {  align-self: baseline; }
  .as-s-m {  align-self: stretch; }
  .as-i-m {  align-self: inherit; }
}

@media screen and (min-width: 64em)  {
  .as-a-l {  align-self: auto; }
  .as-fs-l { align-self: flex-start; }
  .as-fe-l { align-self: flex-end; }
  .as-c-l {  align-self: center; }
  .as-b-l {  align-self: baseline; }
  .as-s-l {  align-self: stretch; }
  .as-i-l {  align-self: inherit; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2015 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

