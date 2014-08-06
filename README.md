# SUIT CSS components-media

A SUIT CSS component that provides a [media object](http://www.stubbornella.org/content/2010/06/25/the-media-object-saves-hundreds-of-lines-of-code/), commonly used for things like comments.

Read more about [SUIT CSS's design principles](https://github.com/suitcss/suit/).

## Installation

* [npm](http://npmjs.org/): `npm install suitcss-components-media`
* [Component(1)](https://github.com/component/component/): `component install simonsmith/components-media`
* [Bower](http://bower.io/): `bower install suitcss-components-media`

## Available classes

* `Media` - [core] The core media component
* `Media--alignRight` - [modifier] Align the media object to the right

## Configurable variables

* `--Media-heading-margin`
* `--Media-object-gutter`

## Use

Example:

```html
<div class="Media">
  <div class="Media-object">
    <img src="http://lorempixel.com/80/80/" alt="">
  </div>
  <div class="Media-body">
    <h2 class="Media-heading">Heading</h2>
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque
    venenatis interdum urna, quis sodales mauris rutrum quis.
  </div>
</div>
```

## Testing

Install [Node](http://nodejs.org) (comes with npm).

```
npm install
```

To generate a build:

```
npm run build
```

To generate the testing build.

```
npm run build-test
```

Basic visual tests are in `test/index.html`.

## Browser support

* Google Chrome
* Firefox
* Opera
* Safari
* Internet Explorer 8+