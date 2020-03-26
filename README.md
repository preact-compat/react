So you're a [Preact](https://preactjs.com/) user, but want to use some React libraries with it. You wanted to [set up aliases or something](https://preactjs.com/guide/v10/getting-started#aliasing-react-to-preact), but can't do it for some reason.

The `preact-compat/react` and `preact-compat/react-dom` alias repositories are here for you!
Install them as you would any other npm module, and these aliases will be used from Github:

```sh
# Preact 10+
npm i -S preact-compat/react#1.x preact-compat/react-dom#1.x
# Older Preact versions
npm i -S preact-compat/react#0.x preact-compat/react-dom#0.x
```

... or for Yarn users:

```sh
# Preact 10+
yarn add preact-compat/react#1.x preact-compat/react-dom#1.x
# Older Preact versions
yarn add preact-compat/react#0.x preact-compat/react-dom#0.x
```
