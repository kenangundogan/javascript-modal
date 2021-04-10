# javascript-modal
Javascript modal - tiny and simple.

![Javascript Modal](https://raw.githubusercontent.com/kenangundogan/javascript-modal/main/asset/javascript-modal-cover.png)

<p>
<a href="https://github.com/kenangundogan/javascript-modal/blob/master/dist/style/style.css"><img src="http://img.badgesize.io/kenangundogan/javascript-modal/master/dist/style/style.css?compression=gzip&label=CSS+gzip+size" alt="CSS gzip size"></a>

<a href="https://github.com/kenangundogan/javascript-modal/blob/master/dist/script/script.js"><img src="http://img.badgesize.io/kenangundogan/javascript-modal/master/dist/script/script.js?compression=gzip&label=CSS+gzip+size" alt="JS gzip size"></a>
</p>

## Options
Option | Type | Default | Description | Example
------ | ---- | ------- | ----------- | -----------
id | string |  | id DOM element | [Example](https://kenangundogan.github.io/javascript-modal/index)
data-position | string | center | special class can be added | [Example](https://kenangundogan.github.io/javascript-modal/index)
data-size | string | small | special class can be added | [Example](https://kenangundogan.github.io/javascript-modal/index)
data-transition | int | 300ms | opening and closing animation speed | [Example](https://kenangundogan.github.io/javascript-modal/index)

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
