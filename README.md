[![License](http://img.shields.io/badge/license-MIT-green.svg?style=flat)](https://github.com/Klaudeta/the-carousel/blob/master/LICENSE)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/Klaudeta/the-carousel)

# \<the-carousel\>

A polymer 2.0 element used to scroll between a list of images

## Installation

```
  bower install  klaudeta/the-carousel
```

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="the-carousel.html">
    <custom-style>
          <style is="custom-style" >
            the-carousel{
              	width: 100%;
               height:374px;
            } 
          </style>
        </custom-style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<the-carousel autoplay duration=5000
            images='["../images/snow.JPG","../images/red.JPG","../images/ship.JPG"]'></the-carousel>
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

MIT License