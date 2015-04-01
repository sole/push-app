# push-app

> Push a Firefox OS app to a client, uninstalling first if need be

[![Install with NPM](https://nodei.co/npm/push-app.png?downloads=true&stars=true)](https://nodei.co/npm/push-app/)

## Example

```javascript
var pushApp = require('push-app');

pushApp(client, pathToApp).then(function(installResults) {
	// ...
});
```

where

* `client` is an instance of [firefox-client](https://github.com/harthur/firefox-client)
* `pathToApp` is the path in the file system to the Firefox OS app you want to be installed in the client
