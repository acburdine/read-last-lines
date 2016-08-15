# Read Last N Lines

Read in the last N lines of a file efficiently using node.js and fs.

## Installation

``` bash
npm install read-last-lines --save
```

## Usage

example reading last 50 lines of a file
``` javascript
const readLastLines = require('read-last-lines');
readLastLines.read('path/to/file', 50)
	.then((lines) => console.log(lines));
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D