Changelog
=========

## [11.0.0](https://github.com/ckeditor/ckeditor5-editor-inline/compare/v10.0.1...v11.0.0) (2018-07-18)

### Features

* Editor can now be created with initial data passed to the constructor. Closes [#37](https://github.com/ckeditor/ckeditor5-editor-inline/issues/37). ([cfd8c53](https://github.com/ckeditor/ckeditor5-editor-inline/commit/cfd8c53))

### Other changes

* Used the `EditorUI` as a parent class for the `InlineEditorUI` (see [ckeditor/ckeditor5-core#130](https://github.com/ckeditor/ckeditor5-core/issues/130)). ([c148346](https://github.com/ckeditor/ckeditor5-editor-inline/commit/c148346))

### BREAKING CHANGES

* The `InlineEditor#element` property was renamed to `InlineEditor#sourceElement` and `InlineEditor#updateElement()` method to `InlineEditor#updateSourceElement()`. See [ckeditor/ckeditor5-core#64](https://github.com/ckeditor/ckeditor5-core/issues/64).


## [10.0.1](https://github.com/ckeditor/ckeditor5-editor-inline/compare/v10.0.0...v10.0.1) (2018-06-21)

Internal changes only (updated dependencies, documentation, etc.).


## [10.0.0](https://github.com/ckeditor/ckeditor5-editor-inline/compare/v1.0.0-beta.4...v10.0.0) (2018-04-25)

### Other changes

* Changed the license to GPL2+ only. See [ckeditor/ckeditor5#991](https://github.com/ckeditor/ckeditor5/issues/991). ([4a6d43a](https://github.com/ckeditor/ckeditor5-editor-inline/commit/4a6d43a))

### BREAKING CHANGES

* The license under which CKEditor 5 is released has been changed from a triple GPL, LGPL and MPL license to a GPL2+ only. See [ckeditor/ckeditor5#991](https://github.com/ckeditor/ckeditor5/issues/991) for more information.


## [1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-editor-inline/compare/v1.0.0-beta.2...v1.0.0-beta.4) (2018-04-19)

Internal changes only (updated dependencies, documentation, etc.).


## [1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-editor-inline/compare/v1.0.0-beta.1...v1.0.0-beta.2) (2018-04-10)

Internal changes only (updated dependencies, documentation, etc.).


## [1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-editor-inline/compare/v1.0.0-alpha.2...v1.0.0-beta.1) (2018-03-15)

### Other changes

* Migrated the editor styles to PostCSS (see [ckeditor/ckeditor5-ui#144](https://github.com/ckeditor/ckeditor5-ui/issues/144)). ([9fbecae](https://github.com/ckeditor/ckeditor5-editor-inline/commit/9fbecae))
* Removed the `.ck-editor-toolbar` class from the toolbar (see [ckeditor/ckeditor5-theme-lark#135](https://github.com/ckeditor/ckeditor5-theme-lark/issues/135)). ([213ddfd](https://github.com/ckeditor/ckeditor5-editor-inline/commit/213ddfd))


## [1.0.0-alpha.2](https://github.com/ckeditor/ckeditor5-editor-inline/compare/v1.0.0-alpha.1...v1.0.0-alpha.2) (2017-11-14)

### Other changes

* Aligned UI library usage to the [changes in the UI framework](https://github.com/ckeditor/ckeditor5-ui/pull/332).


## [1.0.0-alpha.1](https://github.com/ckeditor/ckeditor5-editor-inline/compare/v0.2.0...v1.0.0-alpha.1) (2017-10-03)

Internal changes only (updated dependencies, documentation, etc.).


## [0.2.0](https://github.com/ckeditor/ckeditor5-editor-inline/compare/v0.1.1...v0.2.0) (2017-09-03)

### Bug fixes

* `InlineEditor.create()` should be able to create an instance of its subclass. Closes [#25](https://github.com/ckeditor/ckeditor5-editor-inline/issues/25). ([1da0563](https://github.com/ckeditor/ckeditor5-editor-inline/commit/1da0563))
* Editor element should be filled up with data once the editor is destroyed. Closes [#19](https://github.com/ckeditor/ckeditor5-editor-inline/issues/19). ([fe7d27b](https://github.com/ckeditor/ckeditor5-editor-inline/commit/fe7d27b))
* The toolbar should not collapse when the window is narrow. Closes [#11](https://github.com/ckeditor/ckeditor5-editor-inline/issues/11). ([705dbe5](https://github.com/ckeditor/ckeditor5-editor-inline/commit/705dbe5))

### Features

* The toolbar should support a vertical offset from the top of the web page. Closes [#23](https://github.com/ckeditor/ckeditor5-editor-inline/issues/23). ([01e29d5](https://github.com/ckeditor/ckeditor5-editor-inline/commit/01e29d5))

### Other changes

* Renamed the InlineEditor file to "inlineeditor.js" to match the naming convention. Closes [#6](https://github.com/ckeditor/ckeditor5-editor-inline/issues/6). ([dac7551](https://github.com/ckeditor/ckeditor5-editor-inline/commit/dac7551))

### BREAKING CHANGES

* The `inline.js` file containing `InlineEditor` class has been renamed to `inlineeditor.js`.


## [0.1.1](https://github.com/ckeditor/ckeditor5-editor-inline/compare/v0.1.0...v0.1.1) (2017-05-07)

### Bug fixes

* The position of the floating toolbar should be updated after the editable has grown. Closes [#4](https://github.com/ckeditor/ckeditor5-editor-inline/issues/4). ([ae578b3](https://github.com/ckeditor/ckeditor5-editor-inline/commit/ae578b3))


## 0.1.0 (2017-04-05)

### Features

* Introduced the inline editor. Closes: [#1](https://github.com/ckeditor/ckeditor5-editor-inline/issues/1). ([30c999f](https://github.com/ckeditor/ckeditor5-editor-inline/commit/30c999f))
