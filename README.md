# Monkey-patching Express

"[Express](http://expressjs.com/) is a minimal and flexible [node.js](http://nodejs.org) web application framework, providing a robust set of features for building single and multi-page, and hybrid web applications."

However, there are some minor issues; primarily named routing is [never officially going to happen](https://github.com/visionmedia/express/issues/401), and this fixes that problem. You probably won't find this useful, but it scratches some itches for me.

The source is available for download from
[GitHub](http://github.com/andrewhayward/express-monkey-patch).
Alternatively, you can install using Node Package Manager (npm):

    npm install express-monkey-patch


## Usage

```javascript
const express = require('express');

var app = express();
require('express-monkey-patch')(app);
```
