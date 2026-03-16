# hexo-theme-webstack2

[中文文档](https://github.com/jackkke/hexo-theme-webstack/blob/master/README_CN.md)

> A Hexo theme based on [WebStackPage](https://github.com/WebStackPage/WebStackPage.github.io) and [hexo-theme-webstack](https://github.com/HCLonely/hexo-theme-webstack).

## Installation

```shell
npm install hexo-theme-webstack2 --save
```

or

```shell
cnpm install hexo-theme-webstack2 --save
```

## Configuration

For detailed configuration options, please refer to the original [hexo-theme-webstack documentation](https://github.com/HCLonely/hexo-theme-webstack/blob/master/README.md).


### JS Change

> CDN JavaScript resources configuration.

Local JavaScript files (header.js, footer.js, resizeable.min.js, joinable.js, xenon-api.min.js, xenon-toggles.min.js, xenon-custom.min.js) are built-in and cannot be configured. Only the following CDN resources are configurable:

- jquery: jQuery library
- bootstrap: Bootstrap JS
- TweenMax: GSAP TweenMax
- lozad: Lazy loading library
- busuanzi: Website statistics

Example:
```yml
js:
  jquery: //cdn.jsdelivr.net/npm/jquery@1.11.1/dist/jquery.min.js
  bootstrap: //cdn.jsdelivr.net/npm/bootstrap@3.3.1/dist/js/bootstrap.min.js
  TweenMax: //cdn.jsdelivr.net/npm/gsap@1.13.2/src/minified/TweenMax.min.js
  lozad: //cdn.jsdelivr.net/npm/lozad@1.16.0/dist/lozad.min.js
  busuanzi: //cdn.jsdelivr.net/npm/busuanzi@2.3.0/bsz.pure.mini.min.js
```

### CSS Change

> CDN CSS resources configuration.

Local CSS files (hclonely.css, linecons.min.css, xenon-core.min.css, xenon-components.min.css, xenon-skins.min.css, nav.min.css) are built-in and cannot be configured. Only the following CDN resources are configurable:

- fonts: Google Fonts
- fontawesome: Font Awesome
- bootstrap: Bootstrap CSS

Example:
```yml
css:
  fonts: //fonts.loli.net/css?family=Arimo:400,700,400italic
  fontawesome: https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@5.13.0/css/all.min.css
  bootstrap: //cdn.jsdelivr.net/npm/bootstrap@3.3.1/dist/css/bootstrap.min.css
```
