This just contains enough package.json and .babelrc to be able to convert JSX into acalls to Preact's `h()` function. It shouldn't change much else, and relies on modern browsers supporting JavaScript Modules to handle module loading, using something like

```html
<script src="index.mjs" type="module"></script>
```
