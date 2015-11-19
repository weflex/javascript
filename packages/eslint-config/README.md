# eslint-config

This package provides .eslintrc as an extensible shared config.

## Usage

```sh
$ npm install --save-dev eslint-config-weflex babel-eslint eslint-plugin-react
```

Add the below to your project `.eslintrc`:

```
{
  "extends": "weflex"
}
```

See [WeFlex's Javascript styleguide](https://github.com/weflex/javascript) and
the [ESlint config docs](http://eslint.org/docs/user-guide/configuring#extending-configuration-files)
for more information.

## Improving this config

Consider adding test cases if you're making complicated rules changes, like
anything involving regexes. Perhaps in a distant future, we could use literate
programming to structure our README as test cases for our .eslintrc?

You can run tests with `npm test`.

You can make sure this module lints with itself using `npm run lint`.

