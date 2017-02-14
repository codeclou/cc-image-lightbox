[![](https://codeclou.github.io/cc-image-lightbox/img/cc-image-lightbox-logo.svg)](https://github.com/codeclou/cc-image-lightbox)

> Lightweight single purpose vanilla-JS image lightbox crafted with CSS3 and inline SVG icons for modern browsers.


## Install

```
$ npm install --save cc-image-lightbox
```

## Usage

**Browser**

```html
<html>
<body>
  <link href="../build/cc-image-lightbox.css" rel="stylesheet" />

  <a href="https://codeclou.github.io/cc-image-lightbox/demo/demo-gallery-02/images/DSC05104.JPG" target="_blank"><img
        src="https://codeclou.github.io/cc-image-lightbox/demo/demo-gallery-02/thumbs/DSC05104.JPG"
        data-cc-lightbox="gallery-02"
        data-cc-title="Image Four"
  /></a>

  <script src="../build/cc-image-lightbox.js"></script>
</body>
</html>
```

**Webpack es6**

JS
```js
import CCImageLightbox from 'cc-image-lightbox';
const ccImageLightbox = new CCImageLightbox();
ccImageLightbox.init();
```
If you use `css-loader` the css is imported by the JS component already.

----

SCSS
```scss
@import "../node_modules/cc-image-lightbox/dist/cc-image-lightbox";
```


## License

MIT © [codeclou.io](./LICENSE.md)
