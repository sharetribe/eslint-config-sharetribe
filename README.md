# Sharetribe ESLint configuration

This package provides Sharetribe's shared [ESLint](http://eslint.org/) configuration. It extends the [eslint-config-airbnb](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb) configuration by disabling many rules related to style and syntax and loosens some errors into warnings.

This enables using the configuration in a hot loading environment like an application created with [create-react-app](https://github.com/facebookincubator/create-react-app/) together with an automatic style and syntax formatter like [Prettier](https://github.com/jlongster/prettier).

## Usage

https://www.npmjs.com/package/eslint-config-sharetribe

Install with `npm`:

    npm install --save-dev eslint-config-sharetribe

or with `yarn`:

    yarn add --dev eslint-config-sharetribe

Then install the required peerDependencies.

Next, create an [ESLint configuration file](http://eslint.org/docs/user-guide/configuring#configuration-file-formats) and extend the `sharetribe` configuration:

**.eslintrc**:

```json
{
  "extends": "sharetribe"
}
```

You can then override rules as you wish in this configuration file.

## Changes

See [CHANGELOG.md](CHANGELOG.md).

## Author

Developed and maintained by [Sharetribe](https://www.sharetribe.com/).

## Licence

MIT
