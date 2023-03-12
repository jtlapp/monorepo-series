# Demo TurboRepo monorepo - centralizing only dev dependencies

This is a version of the [basic monorepo example](https://github.com/vercel/turbo/tree/main/examples/basic) that centralizes dev dependencies but not production dependencies.

## Installation

```sh
npx degit jtlapp/turborepo-series/turbo-basic-hdeps-cconfig myreponame
cd myreponame
pnpm install
turbo build
```