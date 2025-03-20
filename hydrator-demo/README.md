
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/crenshaw-dev/hydrator-demo
# cd into the cloned directory
git checkout 7f1dccb30266d3e830c169a08f8848a8b92299cf
helm template . --name-template cm --namespace cm --include-crds
```