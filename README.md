# aggregation-sort

A Polymer Element showing sorting options as clickable icons.

### Example
```html
<aggregation-sort order-by="{{orderBy}}"></aggregation-sort>
```

### Styling

`<aggregation-sort>` provides the following custom properties and mixins for styling:

Custom property         | Description                 | Default
------------------------|-----------------------------|---------------------
`--default-icon-color`  | Color for sort icons        | --paper-grey-600
`--icon-hover-color`    | Icon color in hover         | --paper-blue-800
`--selected-icon-color` | Color of selected sort icon | --paper-blue-grey-800

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

