
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/crenshaw-dev/hydrator-demo
# cd into the cloned directory
git checkout cc2e15c28ff89508b12f9c1213e4d2c339c1431a
helm template . --name-template cm --namespace cm --include-crds
```