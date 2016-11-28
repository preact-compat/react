So you're a [Preact](https://preactjs.com/) user, but want to use some React libraries with it. You wanted to [set up aliases or something](https://preactjs.com/guide/switching-to-preact#easy-preact-compat-alias), but can't do it for some reason. The solution is simple, though:

```
yarn add preact preact-compat
yarn add preact-compat/react preact-compat/react-dom
```

Or if you're not a fan of [yarn](http://yarnpkg.com/):

```
npm i -S preact preact-compat
npm i -S preact-compat/react preact-compat/react-dom
```
