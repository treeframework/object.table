# Table

Some useful helpers for common table patterns.

## Dependencies

The `table` object depends on three other modules:

* [settings.defaults](https://github.com/treeframework/settings.defaults)
* [tools.functions](https://github.com/treeframework/tools.functions)
* [generic.normalize](https://github.com/treeframework/generic.normalize)

If you install the `table` object using Bower or npm, you will get these 
dependencies at the same time. If not using Bower or npm, please be sure to 
install and `@import` these dependencies in the relevant way.

## Installation

You can install `table` module via Bower, npm, or copy and paste.

## Install using Bower:

```sh
$ bower install tree-table --save
```

Once installed, `@import` into your project in its Object layer:

```scss
@import "bower_components/tree-table/object.table";
```

Install using npm:

```sh
$ npm install tree-table --save
```

The least recommended option for installation is to simply download
`_object.table.scss` into your project and `@import` it into your project in its
Objects layer.

## Usage

Basic usage of the `table` object uses the required classes:

```html
<table class="o-table">...</table>
```

## Options

Other, optional classes can supplement the required base classes:

* `.o-table--fixed`: force tables into having equal-width columns.
* `.o-table--compact`: tightly packed cells.
* `.o-table--cosy`: lightly packed cells.
* `.o-table--comfy`: very widely padded cells.
* `.o-table--cells`: adds border around a table.
* `.o-table--rows`: adds border only to table's rows.
* `.o-table--columns`: adds border only to table's columns.

For example:

```html
<table class="o-table  o-table--cosy">...</table>
```

## Credits

* **[inuitcss](https://github.com/inuitcss)** Powerful, Sass-based, OOCSS
framework designed with scalability and performance in mind.

