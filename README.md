# monorepo-series

Example monorepos for my "Sharing TypeScript with Nx and Turborepo" series

## Archive of with-tailwind

The `with-tailwind` directory contains an archive of Vercel's [`with-tailwind` example monorepo](https://github.com/vercel/turbo/tree/main/examples/with-tailwind), copied on February 25, 2023. My series references this archive because this is the version of the example that it describes, in case the original example changes.

## Variations of basic monorepo

These examples are all variations of Turborepo's [official basic example](https://github.com/vercel/turbo/tree/main/examples/basic):

- [turbo-basic-cdeps-cconfig](https://github.com/jtlapp/turborepo-series/tree/main/turbo-basic-cdeps-cconfig) - Centrally manages all dependencies, centrally manages configuration in the monorepo root
- [turbo-basic-hdeps-cconfig](https://github.com/jtlapp/turborepo-series/tree/main/turbo-basic-hdeps-cconfig) - Centrally manages only dev dependencies, centrally manages configuration in the monorepo root
- [turbo-basic-ideps-cconfig](https://github.com/jtlapp/turborepo-series/tree/main/turbo-basic-ideps-cconfig) - Packages individually manages all non-configuration dependencies, centrally manages configuration in the monorepo root
- [turbo-basic-ideps-wconfig](https://github.com/jtlapp/turborepo-series/tree/main/turbo-basic-ideps-wconfig) - Packages individually manages all non-configuration dependencies, centrally manages configuration in configuration workspaces (a snapshot of the [official basic example](https://github.com/vercel/turbo/tree/main/examples/basic))
