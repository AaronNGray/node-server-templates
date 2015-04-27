# node-server-templates
Optimized express serverside Underscore based templates, using consolidate like logic.

## Express 3.x example

```js

var express = require('express');
var templates = require('node-server-templates');

var app = express();

// assign the node-server-templates engine to .tmpl files
app.engine('tmpl', templates);

// view engine setup
app.set('views', path.join(__dirname, 'views'));
app.set('view engine', 'tmpl')
```

## Attributions

- Underscore.js 1.8.2
   - http://underscorejs.org
   - (c) 2009-2015 Jeremy Ashkenas, DocumentCloud and Investigative Reporters & Editors
   - MIT Licensed
- Consolidate.js 0.12.0
   - Copyright(c) 2012 TJ Holowaychuk <tj@vision-media.ca>
   - MIT Licensed

## License

(The MIT License)

Copyright (c) 2011 TJ Holowaychuk &lt;tj@vision-media.ca&gt;

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
