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

### Styling

`<double-bar-chart>` provides the following custom properties and mixins for styling:

Custom property                                  | Description                                               | Default
-------------------------------------------------|-----------------------------------------------------------|--------
`--double-bar-chart-bar-left-color`              | The color of the left bars.                               | --paper-grey-300
`--double-bar-chart-bar-left-count-color`        | The color of the left count labels.                       | --paper-grey-900
`--double-bar-chart-bar-left-height`             | The height of the left bars.                              | 20px
`--double-bar-chart-bar-left-title-color`        | The color of the left title labels.                       | --paper-grey-900
`--double-bar-chart-bar-left-title-hover-color`  | The color of the left title labels on hover (if a link).  | --paper-indigo-900
`--double-bar-chart-bar-right-color`             | The color of the right bars.                              | --paper-grey-300
`--double-bar-chart-bar-right-count-color`       | The color of the right count labels.                      | --paper-grey-900
`--double-bar-chart-bar-right-height`            | The height of the right bars.                             | 20px
`--double-bar-chart-bar-right-title-color`       | The color of the right title labels.                      | --paper-grey-900
`--double-bar-chart-bar-right-title-hover-color` | The color of the right title labels on hover (if a link). | --paper-indigo-900

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

