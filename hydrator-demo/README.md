
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/crenshaw-dev/hydrator-demo
# cd into the cloned directory
git checkout 94195f5ccbfb0cdeda7c55d89f5b262493f0e269
helm template . --name-template cm --namespace cm --include-crds
```