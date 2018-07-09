# preact-cli-svg-loader

Removes svg extension from file-loader, url-loader and raw-loader and use preact-svg-loader to load svg file as preact components



## Getting Started

Install it via npm:

```shell
npm install preact-cli-svg-loader
```

yarn:

```shell
yarn add preact-cli-svg-loader --dev
```

And include in your project by creating a `preact.config.js`

```javascript
const preactCliSvgLoader = require('preact-cli-svg-loader');

export default function (config, env, helpers) {
	preactCliSvgLoader(config, helpers);
}
```

Import your svg files as preact compoments

## License

MIT
