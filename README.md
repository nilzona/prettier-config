# @nilzona/prettier-config

Use this in projects to get a simple and coherent prettier experience.

## info

This config is very simple. The only difference from the default config is:

```json
"printWidth": 120,
```

and it adds two prettier plugins

```json
"plugins": ["prettier-plugin-organize-imports", "prettier-plugin-packagejson"]
```

These plugins organize imports and package.json entries in alphabetic order.

## usage

install package as a dev dependency with your favourite package manager. E.g.

```shell
npm install -d @nilzona/prettier-config
```

and reference it in `package.json`

```json
{
  "name": "my-project",
  "version": "888.0.1",
  "prettier": "@nilzona/prettier-config"
}
```

more instructions on shared prettier configs can be found [here](https://prettier.io/docs/en/configuration.html#sharing-configurations)
