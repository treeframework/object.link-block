# link-block

The `link-block` module simply displays a link as block.

## Dependencies

The `link-block` module depends on one other module:

* [settings.defaults](https://github.com/treeframework/settings.defaults)

If you install the `link-block` module using Bower or npm, you will get these
dependencies at the same time. If not using Bower or npm, please be sure to
install and @import these dependencies in the relevant way.

## Installation

You can install `link-block` module via Bower, npm, or copy and paste.

### Install using Bower:

```sh
$ bower install tree-link-block --save
```

Once installed, `@import` into your project in its Trump layer:

```scss
@import "bower_components/tree-link-block/trump.link-block";
```

### Install using npm:

```sh
$ npm install tree-link-block --save
```

### Install via file download

The least recommended option for installation is to simply download
`_trump.link-block.scss` into your project and `@import` it into your
project in its Trump layer.

## Usage

Basic usage of the `link-block` module uses the required classes:

```html
<a class="u-link-block" href="#">...</a>
```

## Credits

* **[SUIT CSS link utilities](https://github.com/suitcss/utils-link/)** SUIT
CSS is a reliable and testable styling methodology for component-based UI
development.

* **[inuitcss](https://github.com/inuitcss)** Powerful, Sass-based, OOCSS
framework designed with scalability and performance in mind.
