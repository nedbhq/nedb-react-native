# nedb-react-native

> NeDB for React Native

**This is an experimental work in progress. Not ready for use.**

## Installation

```
npm install nedb-react-native --save
```

## Documentation

TODO

## Complete Example

```js
const Datastore = require('nedb-react-native');

const db = new Datastore('file://users.db');

db.find({}, function(error, users) {

});
```

## License

Copyright (c) 2016

Licensed under the [MIT license](LICENSE).
