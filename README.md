# mdPickers
Material Design date/time pickers built with Angular Material and Moment.js. Inline pickers utilize md-menu for display and selection.


## Online demos

[TODO]


## Requirements

* [moment.js](http://momentjs.com/)
* [AngularJS](https://angularjs.org/)
* [Angular Material](https://material.angularjs.org/)
* [Material Design Icons](http://google.github.io/material-design-icons/#icon-font-for-the-web)

## Using mdPickers

Install via Bower:

```bash
bower install mdInlinePickers
```

Use in Angular:
```javascript
angular.module( 'YourApp', [ 'mdPickers' ] )
  .controller("YourController", YourController );
```

## Building mdPickers

First install or update your local project's __npm__ tools:

```bash
# First install all the npm tools:
npm install

# or update
npm update
```

Then run the default gulp task:

```bash
# builds all files in the `dist` directory
gulp
```
