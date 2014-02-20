*This repository is a mirror of the [component](http://component.io) module [ianstormtaylor/to-camel-case](http://github.com/ianstormtaylor/to-camel-case). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/ianstormtaylor-to-camel-case`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# to-camel-case

  Convert a string to a camel case.

## Installation

    $ component install ianstormtaylor/to-camel-case
    $ npm install to-camel-case

_Big thanks to [@Nami-Doc](https://github.com/Nami-Doc) for graciously giving up the npm package name :)_

## Example

```js
var camel = require('to-camel-case');

camel('space case'); // "spaceCase"
camel('snake_case'); // "snakeCase"
camel('dot.case');   // "dotCase"
camel('weird[case'); // "weirdCase"
```

## API

### toCamelCase(string)
  
  Returns the camel-case variant of a `string`.

## License

  MIT
