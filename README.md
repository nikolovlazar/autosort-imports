# Autosort imports!

A demo project that implements the
[@trivago/prettier-plugin-sort-imports](https://npmjs.com/package/@trivago/prettier-plugin-sort-imports)
plugin for Prettier that autosorts your imports.

## How to set it up

1. Install `@trivago/prettier-plugin-sort-imports` as a dev dependency
2. Add `"plugins": ["@trivago/prettier-plugin-sort-imports"]` in your
   [`.prettierrc`](./.prettierrc) file
3. Configure your import order with the `importOrder` property.
4. Set `importOrderSeparation` to `true` if you want an empty line between the
   import groups.
5. Set `importOrderSortSpecifiers` to `true` if you want to auto sort named
   imports as well.
