## elasticsearch-elements
Aggregation component for elasticsearch-elements.

An elasticsearch UI build with [web components](http://webcomponents.org/) / [polymer](http://www.polymer-project.org/) using and Google's [material design](http://www.google.com/design/spec/material-design/introduction.html) / [paper elements](http://www.polymer-project.org/docs/elements/paper-elements.html#paper-button). The goal is to create custom elements with similar functionality to [kibana](http://www.elasticsearch.org/overview/kibana/)'s panels. Web components will allow these to be used anywhere, in any elasticsearch plugin!

## Install
```js
bower install elasticsearch-elements --save
```

## Include
```html
<!-- shim web components -->
<script src="/bower_components/platform/platform.js"></script>

<!-- include all elasticsearch elements, this can also be done one at a time -->
<link rel="import" href="/bower_components/elasticsearch-elements.html">

<!-- example element to display http://localhost:9200/twitter/_status -->
<elasticsearch-index-status host="http://localhost:9200" index="twitter"></elasticsearch-index-status>
```

## Elements
- [elasticsearch-status](http://erikringsmuth.github.io/elasticsearch-status/components/elasticsearch-status/)
- [elasticsearch-index-status](http://erikringsmuth.github.io/elasticsearch-index-status/components/elasticsearch-index-status/)

## Contributing
Submit PRs to add elements to this list.
