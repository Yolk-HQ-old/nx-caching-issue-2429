# nx-caching-example

Example demonstrating an issue with Nx's new caching feature and `@nrwl/next`.

### Usage

```shell
yarn

yarn nx run myapp:build:production
# observe: myapp is compiled

yarn nx run myapp:serve:production
# observe: myapp is compiled *again*
```
