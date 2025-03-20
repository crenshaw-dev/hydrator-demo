
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/crenshaw-dev/hydrator-demo
# cd into the cloned directory
git checkout 356eb8443a12c9fcaec0ff554c7c6075d6c932a0
helm template . --name-template cm --namespace cm --include-crds
```