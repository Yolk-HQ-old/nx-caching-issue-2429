# nx-caching-issue-2429

Example demonstrating an issue with Nx's new caching feature and `@nrwl/next`.

See https://github.com/nrwl/nx/issues/2429

### Usage

```shell
yarn

yarn nx run myapp:build:production
# observe: myapp is compiled

yarn nx run myapp:serve:production
# observe: myapp is compiled *again*
```
