# npms-api

[![Build status][travis-image]][travis-url] [![Coverage status][codecov-image]][codecov-url] [![Dependency status][david-dm-image]][david-dm-url] [![Dev dependency status][david-dm-dev-image]][david-dm-dev-url]

The https://npms.io API.

You may read the API documentation in https://api-docs.npms.io.

The API is available under `https://api.npms.io/v<version>`, where `version` may be:
- `2` (current)
- `1` (deprecated, unavailable since `2016-12-19`


## Development

Simply spawn the server by running `$ npm run start-dev`.


## Deploys

There's a separate document that explains the deployment procedure, you may read it [here](./docs/deploys.md).


## Documentation

You may update the API REST documentation by running `$ npm run docs` and previewing `docs/apidoc/index.html` in your browser.

To push any changes in the documentation run `$ npm run docs-push`.


## Tests

```bash
$ npm test
$ npm test-cov # to get coverage report
```


## License

Released under the [MIT License](http://www.opensource.org/licenses/mit-license.php).


[codecov-url]:https://codecov.io/gh/npms-io/npms-api
[codecov-image]:https://img.shields.io/codecov/c/github/npms-io/npms-api/master.svg
[david-dm-dev-image]: https://img.shields.io/david/dev/npms-io/npms-api.svg
[david-dm-dev-url]: https://david-dm.org/npms-io/npms-api#info=devDependencies
[david-dm-image]: https://img.shields.io/david/npms-io/npms-api.svg
[david-dm-url]: https://david-dm.org/npms-io/npms-api
[travis-image]: http://img.shields.io/travis/npms-io/npms-api/master.svg
[travis-url]: https://travis-ci.org/npms-io/npms-api
