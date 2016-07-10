# superagent
Fork of (visionmedia/superagent)[https://github.com/visionmedia/superagent

Adds more `options` to the `superagent.agent` like `ca`, `cert`, `disableIdentityCheck` and `headers` so they dont have to be set on each request.

## Example:
```js
const sslAgent = superagent.agent({
  ca: rootCA,
  cert: client.cert,
  key: client.key,
  disableIdentityCheck: true,
  headers: {
    'foo': 'bar'
  }
});
```

## Installation

node:

```
$ npm install git+https://github.com/wemakeweb/superagent.git
```

## License

MIT
