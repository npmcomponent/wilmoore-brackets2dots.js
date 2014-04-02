*This repository is a mirror of the [component](http://component.io) module [wilmoore/brackets2dots.js](http://github.com/wilmoore/brackets2dots.js). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/wilmoore-brackets2dots.js`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# brackets2dots.js [![Build Status](https://travis-ci.org/wilmoore/brackets2dots.js.png?branch=master)](https://travis-ci.org/wilmoore/brackets2dots.js) [![NPM version](https://badge.fury.io/js/brackets2dots.png)](http://badge.fury.io/js/brackets2dots) [![Dependency Status](https://gemnasium.com/wilmoore/brackets2dots.js.svg)](https://gemnasium.com/wilmoore/brackets2dots.js)

  Convert string with bracket notation to dot property notation for [Node.js][] and the browser.

## Example

    var brackets2dots = require('brackets2dots');

    brackets2dots('group[0].section.a.seat[3]')
    //=> 'group.0.section.a.seat.3'

## Installation

[component](http://component.io/wilmoore/brackets2dots)

    $ component install wilmoore/brackets2dots

[bower](http://sindresorhus.com/bower-components/)

    $ bower install brackets2dots.js

[npm](https://npmjs.org/package/brackets2dots)

[![NPM](https://nodei.co/npm/brackets2dots.png?downloads=true)](https://nodei.co/npm/brackets2dots/)

[volo](http://volojs.org)

    $ volo add wilmoore/brackets2dots.js

[manual][]

1. download

        % curl -#O https://raw.github.com/wilmoore/brackets2dots.js/master/brackets2dots.js

2. use

        <script src="brackets2dots.js"></script>

## Inspiration

- [selectn][]

## License

  MIT

[selectn]:  https://github.com/wilmoore/selectn
[global]:   https://raw.github.com/wilmoore/brackets2dots.js/master/brackets2dots.min.js
[Node.js]:  http://nodejs.org
[manual]:   http://yuiblog.com/blog/2006/06/01/global-domination/

