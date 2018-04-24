# categorised-url.js

Categorises URLs and extracts inferable meta-data from them. Currently supporting `Facebook`, `Instagram`, `Twitter`, `Vimeo`, `Vine` and `YouTube`.

## Installation

Install the npm package:

```bash
npm install categorised-url.js
```

Import as a module:

```js
// ES6 module
import CategorisedUrl from 'categorised-url.js';

// CommonJS
const CategorisedUrl = require('./categorised-url.js');
```

Or load the minified library:

```html
<script type="text/javascript" src="node_packages/categorised-url.js/dist/categorised-url.min.js"></script>
```

## Usage

```js
var urlMetadata = CategorisedUrl.fromUrl('https://www.youtube.com/watch?v=x8wC-WxC31s');
```

### Meta Data

* url: Url provided
* provider: One of the providers above
* resource_type: User or Media
* resource: Resource ID (either media or user)
* canonical_url: Canonical URL for the resource

## Running / Development

* `git clone <repository-url>` this repository
* `cd categorized-url.js`
* `npm install`

### V2 TODO

* [ ] Update dev dependencies
* [ ] Setup ESLint
* [ ] Setup Travis CI
* [ ] Add release script
* [ ] Update README
* [ ] Publish to npm
