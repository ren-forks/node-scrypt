Fix `scrypt` being added to your `node_modules` every time you run `yarn` when using an incompatible version of `node`.

## Usage

Add to your `package.json`:

```js
  "resolutions": {
    "scrypt": "https://github.com/ren-forks/node-scrypt"
  }
```
