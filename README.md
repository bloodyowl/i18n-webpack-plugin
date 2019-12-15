# inline-translations-webpack-plugin

> A fork of the deprecated i18n-webpack-plugin

## Installation

```console
$ yarn add inline-translations-webpack-plugin
```

## Usage

```js
let InlineTranslationPlugin = require("inline-translations-webpack-plugin");

new InlineTranslationPlugin(translations);
```

Every occurence of `__("Translation")` in your sources will be replaced with the inline string of the translation.

If you don't provide a translations dictionnary, the first argument is inlined. A common recipe is to use the default language translation as a key.

