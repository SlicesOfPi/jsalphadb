# jsalphadb
Database system for NodeJS &amp; Port of phpAlphaDB
Version: 1.0

## Installation
I recommend you install from NPM<br>
`npm install jsalphadb`<br>
<br>
Put this at the top of your javascript file.

```js
var key = "Something"; // The secret key, though theres no point to changing it.
var ext = ".4db"; // The extension of the database.

const jsAlphaDB = require("jsalphadb");
const db = new jsAlphaDB(key, ext);
```
Make sure node is allowed to write to the filesystem.

## Description
This is a JavaScript Remake of the flatfile database system made by JQuery<br>
The purpose is to create a basic, easy to learn & use flat database system for applications

## License
WTFPL - http://www.wtfpl.net/
