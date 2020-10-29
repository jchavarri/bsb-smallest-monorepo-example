# BuckleScript smallest monorepo example

A small example to show a Yarn workspaces / monorepo setup with BuckleScript.

# Build
```
cd app
yarn build
```

# Watch

```
cd app
yarn start
```

# Reproduce watching issues

While the watcher is running in `app` (see section above) update file `my-lib/src/MyLib.re` and notice how the bsb watcher does not pick up changes.