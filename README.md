# double-bar-chart

A Polymer Element showing a bar chart of double-bar elements with optional selectable behavior.

### Example
```html
<double-bar-chart
  client="[[client]]"
  index-name="myIndexName"
  index-types='["myIndexType"]'
  query-field="myQueryField"
  show-checkboxes
  data="[[data]]"
  selected-ids="{{selected}}">
</double-bar-chart>
```

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve

