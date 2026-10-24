# aimlapi-models usage example

Offline JSON-backed AI/ML API / 302.ai unified proxy catalog (200+ models).

This consuming application demonstrates **look up models in the bundled offline catalog** using the published npm package, pinned to `0.3.0`.

## Run

Requires Node.js 24 or newer and npm. The example needs no service credentials.

```sh
npm install --ignore-scripts
npm start
```

## Example

[`src/index.mjs`](src/index.mjs) contains the complete example. Assertions check the demonstrated behavior and the program prints a small result.

## When to use the package

- A consumer needs the following capability: Offline JSON-backed AI/ML API / 302.ai unified proxy catalog (200+ models).
- An application needs the versioned aimlapi-models definitions or bundled content instead of maintaining its own copy.

## Links

- [npm package](https://www.npmjs.com/package/aimlapi-models)
- [Implementation monorepo](https://github.com/x12i/ai-profiles)
- [Reviewed package source](https://github.com/x12i/ai-profiles/tree/8efd4dc11dfaacab2ceef9f030a4a3fa7da00800/packages/aimlapi-models)

The `package.json` in this repository is private to prevent accidental publication of the example application under an npm package name.
