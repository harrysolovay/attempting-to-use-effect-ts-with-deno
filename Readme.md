Issues:

- Effect-ts' module import specifiers reference to-be-transpiled `js` files. This means that importing as GH raw content fails (as none of the referenced JS files are resolved).
- No Deno equivalent of `@effect-ts/node/Runtime`.
