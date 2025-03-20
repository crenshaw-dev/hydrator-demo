
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/crenshaw-dev/hydrator-demo
# cd into the cloned directory
git checkout 8cad7e53b90811cd7d9b1c27532cff4b09fc8a46
helm template . --name-template cm --namespace cm --include-crds
```