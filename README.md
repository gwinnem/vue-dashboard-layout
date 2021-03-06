# What is gwinnem/vue-dashboard-layout?
[It is based on jbaysolutions: vue-grid-layout](https://jbaysolutions.github.io/vue-grid-layout)

New work will be focused on upgrading the vue version to 3.0.0 and refactoring code, so it is proper typescript with new linting rules to ensure better code quality.

## Original Features:
* Draggable widgets.
* Resizable widgets.
* Static widgets.
* Bounds checking for dragging and resizing.
* Widgets may be added or removed without rebuilding the grid layout.
* Layout can be serialized and restored.
* Automatic RTL support.
* Responsive.

## New Features:
* Add Pinia for sharing and updating the state when the layout and the items are changed.

## TODO's
* ~~Update all npm packages.~~
* ~~Change all js files to ts.~~
* Fix new issues in dev ui (App.vue).
    * Prop rowHeight is not a number when being increased in the App.vue file. To be done later since this only affects the dev ui.
* ~~Investigate if interact js can be replaced since it has links to outdated packages with performance issues.~~
    * ~~Not working [Maybe use latest npm](https://www.npmjs.com/package/interactjs)~~
* Refactor prop names.
* Fix warnings in the terminal.
    * ~~App.vue =>  155:13  error  The "CustomDragElement" component has been registered but not used  vue/no-unused-components~~
    * Gridlayout.vue => 336:17  error  Unexpected mutation of "layout" prop  vue/no-mutating-props
    * DOM.ts => 1:15  error  Parsing error: Unexpected token :
    * responsiveUtils.ts => 2:13  error  Parsing error: Unexpected token {
    * utils.ts => 1:8  error  Parsing error: Unexpected token type
* Fix all magic strings and use enums instead.
* Replace interact.js with [sortablejs](https://github.com/SortableJS/Sortable) or [VUE 3 version](https://github.com/SortableJS/vue.draggable.next)
* Extract inline json code for layouts to new files.
* New linting rules.
* Fix all warnings.
* Responsiveness when changing col nums in ui is not correct.
* Create new example files.
* New documentation.
* New build scripts.
* New npm publish scripts.
* Publish work to npm.
* Refactor code in vue files and introduce Pinia store, for storing and sharing state.
* Register domain vue-dashboard-layout and find hosting.
* Create properly styled documentation on new website.
* Create advanced examples on new website using [Quasar framework](https://quasar.dev/), [element-plus framework](https://element-plus.org/en-US/) and [Vue material template](https://www.creative-tim.com/vuematerial).


## Documentation
[Original documentation from jbaysolution](https://jbaysolutions.github.io/vue-grid-layout/guide/)

[New documentation](./docs/TOC.md)


## License
[MIT](./LICENSE.md)



# Contribute


## Code of conduct
[README](./CODE_OF_CONDUCT.md)


## Issues


## Pull requests
