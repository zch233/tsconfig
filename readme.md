# tsconfig

> Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) for my projects

## Install

```sh
yarn add zch-tsconfig -D
// or
npm install --save-dev zch-tsconfig
```

*This config requires TypeScript 4.7 or later.*

## Usage

`tsconfig.json`

```json
{
	"extends": "zch-tsconfig",
	"compilerOptions": {
		"outDir": "dist"
	}
}
```

When you are targeting a higher version of Node.js, check the relevant ECMAScript version and add it as `target`:

```json
{
	"extends": "zch-tsconfig",
	"compilerOptions": {
		"outDir": "dist",
		"target": "ES2021"
	}
}
```
