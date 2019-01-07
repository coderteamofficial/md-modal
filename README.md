# MD Modal

MD Modal based on [Nifty Modal](https://tympanus.net/codrops/2013/06/25/nifty-modal-window-effects/)

## Benefits:

* Clean styles & js - easily create animations
* Created with flexbox

## How to

1. Add CSS and JS

CSS - `<link rel="stylesheet" href="dist/css/style.css">`
JS - `<script src="dist/js/mdmodal.js"></script>`

2. Button Trigger

Using class `md-trigger` and data-modal on a button or anchor.

`<button class="md-trigger" data-modal="modal-1">Show Modal</button>`

3. Structure

The structure of the modal HTML is specific

```
<div class="md-modal md-fade" id="modal-1">
    <div class="md-content">
        <div class="md-close"><span></span><span></span></div>
        <div class="md-title">Modal Dialog</div>
        <div class="md-body">
            <p>This is a modal window. You can do the following things with it:</p>
        </div>
    </div>
</div>
```

An addition div is required (preferably at the bottom) to render the div into.

`<div class="md-overlay"></div>`

## Properties

Made using the preprocessor [Stylus](http://stylus-lang.com/). You can modify style, just change style.styl.

1. Add node modules to your project `yarn`
2. Build `stylus -w dev/css/style.styl -o dist/css/style.css`

## Structure

* dev/ - for development files stylus
* dist/ - for generic files and public files
* package.json - dependencies

## Authors

* **antiden** - [CODERTEAM_](https://coderteam.ru)

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://rem.mit-license.org/) file for details
