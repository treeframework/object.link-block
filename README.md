# link-block

The `link-block` object simply displays a link as block.

## Dependencies

The `link-block` object depends on one other module:

* [settings.defaults](https://github.com/treeframework/settings.defaults)

If you install the `link-block` object using Bower or npm, you will get these
dependencies at the same time. If not using Bower or npm, please be sure to
install and @import these dependencies in the relevant way.

## Installation

You can install `link-block` object via Bower, npm, Git Submodule, or copy and
paste.

### Install using Bower:

```sh
$ bower install tree-link-block --save
```

Once installed, `@import` into your project in its Object layer:

```scss
@import "bower_components/tree-link-block/object.link-block";
```

### Install using npm:

```sh
$ npm install tree-link-block --save
```

### Install as a Git Submodule:

```sh
$ git submodule add git@github.com:treeframework/object.link-block.git
```

Once installed, `@import` into your project in its Object layer:

```scss
@import "object.link-block/object.link-block";
```

### Install via file download

The least recommended option for installation is to simply download
`_object.link-block.scss` into your project and `@import` it into your
project in its Object layer.

## Usage

Basic usage of the `link-block` object uses the required classes:

```html
<a class="link-block" href="#">
    Link block
</a>
```

## Credits

* **[SUIT CSS link utilities](https://github.com/suitcss/utils-link/)** SUIT
CSS is a reliable and testable styling methodology for component-based UI
development.

* **[inuitcss](https://github.com/inuitcss)** Powerful, Sass-based, OOCSS
framework designed with scalability and performance in mind.
