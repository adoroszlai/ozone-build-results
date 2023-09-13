# Ozone Build results archive

This repository will collect the build results (and artifacts) of the master build of Apache Hadoop Ozone.

Artifacts are downloaded with https://github.com/elek/ogh

** Due to the space restrictions only the artifacts of the failed tests are archived **

TODO:

  * Create github actions to download it and commit it automatically
  * Move it to an apache repo when stable
  * Archive all the older artifacts

## Checkout

As this repository is quite huge, it's strongly recommended to checkout only the required parts:

```
git clone --filter=blob:none --no-checkout --sparse https://github.com/adoroszlai/ozone-build-results
cd ozone-build-results
git sparse-checkout add 2023
#or git sparse-checkout add 2023/09
git checkout master
```

