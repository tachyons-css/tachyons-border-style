# tachyons-border-style 2.0.0

Border style CSS module for Tachyons

#### Stats

297 | 16 | 16
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons-border-style
```

#### With Git

```
git clone https://github.com/tachyons-css/tachyons-border-style
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "tachyons-border-style";
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
<link rel="stylesheet" href="path/to/module/css/tachyons-border-style">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*

   BORDER STYLES

   Base:
     bs = border-style

   Modifiers:
     none   = none
     dotted = dotted
     dashed = dashed
     solid  = solid

   Media Query Extensions:
     -ns = not-small
     -m  = medium
     -l  = large

 */
.bs-none { border-style: none; }
.bs-dotted { border-style: dotted; }
.bs-dashed { border-style: dashed; }
.bs-solid { border-style: solid; }
@media screen and (min-width: 48em) {
 .bs-none-ns { border-style: none; }
 .bs-dotted-ns { border-style: dotted; }
 .bs-dashed-ns { border-style: dashed; }
 .bs-solid-ns { border-style: solid; }
}
@media screen and (min-width: 48em) and (max-width: 64em) {
 .bs-none-m { border-style: none; }
 .bs-dotted-m { border-style: dotted; }
 .bs-dashed-m { border-style: dashed; }
 .bs-solid-m { border-style: solid; }
}
@media screen and (min-width: 64em) {
 .bs-none-l { border-style: none; }
 .bs-dotted-l { border-style: dotted; }
 .bs-dashed-l { border-style: dashed; }
 .bs-solid-l { border-style: solid; }
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

