# tachyons-position 3.1.0

Performance based css module.

#### Stats

192 | 12 | 12
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons-position
```

#### With Git

```
git clone https://github.com/tachyons-css/tachyons-position
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "tachyons-position";
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
<link rel="stylesheet" href="path/to/module/css/tachyons-position">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*

    POSITIONING

 */
.pos-stat { position: static; }
.pos-rel { position: relative; }
.pos-abs { position: absolute; }
@media screen and (min-width: 48em) {
 .pos-stat-ns { position: static; }
 .pos-rel-ns { position: relative; }
 .pos-abs-ns { position: absolute; }
}
@media screen and (min-width: 48em) and (max-width: 64em) {
 .pos-stat-m { position: static; }
 .pos-rel-m { position: relative; }
 .pos-abs-m { position: absolute; }
}
@media screen and (min-width: 64em) {
 .pos-stat-l { position: static; }
 .pos-rel-l { position: relative; }
 .pos-abs-l { position: absolute; }
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

