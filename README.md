```
git clone git@github.com:avevlad/ts-node-hello-world.git
npm install
npx ts-node-transpile-only src/index.ts
```

```
npm install typescript ts-node @tsconfig/node16 @types/node --save-dev
```

tsconfig.json
```
{
  "extends": "@tsconfig/node16/tsconfig.json"
}
```