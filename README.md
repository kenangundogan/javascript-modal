# Javascript Modal
Javascript modal - tiny and simple.

## Status
[![JS gzip size](https://img.badgesize.io/kenangundogan/javascript-modal/main/dist/script/script.js?compression=gzip&label=JS%20gzip%20size)](https://github.com/kenangundogan/javascript-modal/blob/main/dist/script/script.js)
[![JS Brotli size](https://img.badgesize.io/kenangundogan/javascript-modal/main/dist/script/script.js?compression=brotli&label=JS%20Brotli%20size)](https://github.com/kenangundogan/javascript-modal/blob/main/dist/style/style.css)
[![CSS gzip size](https://img.badgesize.io/kenangundogan/javascript-modal/main/dist/style/style.css?compression=gzip&label=CSS%20gzip%20size)](https://github.com/kenangundogan/javascript-modal/blob/main/dist/style/style.css)
[![CSS Brotli size](https://img.badgesize.io/kenangundogan/javascript-modal/main/dist/script/script.js?compression=brotli&label=CSS%20Brotli%20size)](https://github.com/kenangundogan/javascript-modal/blob/main/dist/style/style.css)

![Javascript Modal](https://raw.githubusercontent.com/kenangundogan/javascript-modal/main/asset/javascript-modal-cover.png)

## Options
Option | Type | Default | Description | Example
------ | ---- | ------- | ----------- | -----------
id | string |  | id DOM element | [Example](https://kenangundogan.github.io/javascript-modal)
data-position | string | center | special class can be added | [Example](https://kenangundogan.github.io/javascript-modal)
data-size | string | small | special class can be added | [Example](https://kenangundogan.github.io/javascript-modal)
data-transition | int | 300ms | opening and closing animation speed | [Example](https://kenangundogan.github.io/javascript-modal)

## Usage example
### Script
```javascript
var modal = new Modal;
```

### View
```html
<button class="modalBtn" data-target="#modal-default">Default</button>

<div class="modal-container" id="modal-default">
    <div class="modal-wrapper">
        <i class="modal-close"></i>
        ...
    </div>
</div>
```

## Copyright and license
Designed and built by [Kenan Gündoğan](https://www.linkedin.com/in/kenangundogan/)
<br>
2021 Currently - Code released under the [MIT License](https://github.com/kenangundogan/javascript-modal/blob/master/LICENSE)
Docs released under [Creative Commons](https://creativecommons.org/licenses/by/3.0/)
