# css-transform-style 0.0.6

Css module of single purpose classes for transform-style

#### Stats

194 | 12 | 12
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-transform-style
```

#### With Git

```
git clone https://github.com/tachyons-css/css-transform-style
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-transform-style";
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
<link rel="stylesheet" href="path/to/module/css/css-transform-style">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   TRANSFORMS
*/
.ts-p3d { transform-style: preserve-3d; }
.ts-flat { transform-style: flat; }
.ts-i { transform-style: inherit; }
@media screen and (min-width: 48em) {
 .ts-p3d-ns { transform-style: preserve-3d; }
 .ts-flat-ns { transform-style: flat; }
 .ts-i-ns { transform-style: inherit; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .ts-p3d-m { transform-style: preserve-3d; }
 .ts-flat-m { transform-style: flat; }
 .ts-i-m { transform-style: inherit; }
}
@media screen and (min-width: 64em) {
 .ts-p3d-l { transform-style: preserve-3d; }
 .ts-flat-l { transform-style: flat; }
 .ts-i-l { transform-style: inherit; }
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

MIT

