# hexo-theme-webstack2

[English Docs](https://github.com/jackkke/hexo-theme-webstack/blob/master/README.md)

> 一款基于 [WebStackPage](https://github.com/WebStackPage/WebStackPage.github.io) 的 Hexo 主题，由 [hexo-theme-webstack](https://github.com/HCLonely/hexo-theme-webstack) 魔改而来。

## 安装

```shell
npm install hexo-theme-webstack2 --save
```

or

```shell
cnpm install hexo-theme-webstack2 --save
```

## 配置

安装完成后会在根目录生成一个 `_config.webstack2.yml` 文件，直接编辑该文件进行配置即可。详细配置项请参考原版 [hexo-theme-webstack 文档](https://github.com/HCLonely/hexo-theme-webstack/blob/master/README.md)。

### JS 资源配置

> CDN JavaScript 资源配置。

本地 JavaScript 文件（header.js, footer.js, resizeable.min.js, joinable.js, xenon-api.min.js, xenon-toggles.min.js, xenon-custom.min.js）已内置，不可配置。仅以下 CDN 资源可配置：

- jquery: jQuery 库
- bootstrap: Bootstrap JS
- TweenMax: GSAP TweenMax
- lozad: 懒加载库
- busuanzi: 网站统计

示例：

```yml
js:
  jquery: //cdn.jsdelivr.net/npm/jquery@1.11.1/dist/jquery.min.js
  bootstrap: //cdn.jsdelivr.net/npm/bootstrap@3.3.1/dist/js/bootstrap.min.js
  TweenMax: //cdn.jsdelivr.net/npm/gsap@1.13.2/src/minified/TweenMax.min.js
  lozad: //cdn.jsdelivr.net/npm/lozad@1.16.0/dist/lozad.min.js
  busuanzi: //cdn.jsdelivr.net/npm/busuanzi@2.3.0/bsz.pure.mini.min.js
```

### CSS 资源配置

> CDN CSS 资源配置。

本地 CSS 文件（hclonely.css, linecons.min.css, xenon-core.min.css, xenon-components.min.css, xenon-skins.min.css, nav.min.css）已内置，不可配置。仅以下 CDN 资源可配置：

- fonts: Google Fonts
- fontawesome: Font Awesome
- bootstrap: Bootstrap CSS

示例：

```yml
css:
  fonts: //fonts.loli.net/css?family=Arimo:400,700,400italic
  fontawesome: https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@5.13.0/css/all.min.css
  bootstrap: //cdn.jsdelivr.net/npm/bootstrap@3.3.1/dist/css/bootstrap.min.css
```