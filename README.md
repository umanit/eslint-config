# @umanit/eslint-config

#### An ESLint [Shareable Config](http://eslint.org/docs/developer-guide/shareable-configs) for [JavaScript Standard Style](http://standardjs.com)

[![JavaScript Style Guide - Standard Style](https://cdn.rawgit.com/standard/standard/master/badge.svg)](http://standardjs.com)

## Install

```bash
npm install --dev @umanit/eslint-config

# or if you use yarn

yarn add --dev @umanit/eslint-config
```

## Usage

Shareable configs are designed to work with the `extends` feature of `.eslintrc` files.
You can learn more about
[Shareable Configs](http://eslint.org/docs/developer-guide/shareable-configs) on the
official ESLint website.

Add this to your `.eslintrc` file:

```
{
  "extends": "@umanit"
}
```

*Note: We omitted the `/eslint-config` suffix since it is automatically assumed by ESLint.*

You can override settings from the shareable config by adding them directly into your
`.eslintrc` file.

## License

MIT
