
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/crenshaw-dev/hydrator-demo
# cd into the cloned directory
git checkout d806a553770086a7dbefbb0ce6454f2c58462e8b
helm template . --name-template prom --namespace prom --include-crds
```