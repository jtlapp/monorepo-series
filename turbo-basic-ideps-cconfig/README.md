# Demo TurboRepo monorepo - individually managed dependencies

This is a version of the [basic monorepo example](https://github.com/vercel/turbo/tree/main/examples/basic) that individually manages all non-configuration dependencies.

## Installation

```sh
npx degit jtlapp/turborepo-series/turbo-basic-ideps-cconfig myreponame
cd myreponame
pnpm install
turbo build
```