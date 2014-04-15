*This repository is a mirror of the [component](http://component.io) module [airportyh/is-type](http://github.com/airportyh/is-type). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/airportyh-is-type`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
is-type
=======

Simple type checks for Javascript as a component. Adapted from [is-type](https://github.com/juliangruber/is-type) and [core-util-is](https://github.com/isaacs/core-util-is).

## Usage

```js
var is = require('is-type');

is.array([1]); // => true
is.primitive(true); // => true
is.primitive({}); // => false
is.string('hello'); // => true
is.number(4); // => true
```