# is-production

This npm package provides shorthands for determining if the current environment is a production environment. It exports two boolean constants: `isProduction` and `isDevelopment`.

## Installation
You can install the package using npm:

```bash
npm install is-production
```

or using bun: 

```bash
bun add is-production
```

## Usage
You can use the package in your JavaScript or TypeScript projects as follows:
```javascript
import { isProduction, isDevelopment } from 'is-production';
if (isProduction) {
	console.log('Running in production mode');
} else if (isDevelopment) {
	console.log('Running in development mode');
}
```

## Constants
- `isProduction`: A boolean that is `true` if the `NODE_ENV` environment variable is set to `'production'`.
- `isDevelopment`: A boolean that is `true` if the `NODE_ENV` environment variable is set to `""` or `undefined`.

## License
This project is licensed under the MIT License.
