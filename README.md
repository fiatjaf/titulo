This is a brazilian fork of Rod Vagg's [package](https://github.com/rvagg/titlecase) which itself was forked from David Gouch's excellent [`String#toTitleCase()`](https://github.com/gouch/to-title-case) method inspired by John Gruber's [post on the topic](http://daringfireball.net/2008/08/title_case_update).

The current implementation should be used for portuguese strings.

```js
var titulo = require('titulo').toLaxTitleCase
console.log(titulo('deus e o diabo na terra do sol')) // Deus e o Diabo na Terra do Sol
```

```js
var titulo = require('titulo')
console.log(titulo('deus e o diabo na terra do sol')) // Deus E O Diabo Na Terra Do Sol
```
