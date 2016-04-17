# accessibility-alt-tag
Accessibility Alt tag scanner


### Usage

1) include jquery to your page

2) add jquery.alttag.js to your page

3) add this js code:
```js
    jQuery("body").altTag({
        test: true
    }
```

### Default Options
```js
    test : false,
    fix  : true,
    alt  : 'image',
    roleLink : false
```
<p><code>test</code> - log in console how much images you have pn current page without alt tag</p>
<p>fix  - add missed alt tags to images</p>
<p>alt - string, alt value for images</p>
<p>roleLink - add role="link" to each <a> tag on the DOM</p>
