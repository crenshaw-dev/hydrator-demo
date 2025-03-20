
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/crenshaw-dev/hydrator-demo
# cd into the cloned directory
git checkout f1cd870a751d66e87855bd6731b2d8a29c457ae4
helm template . --name-template cm --namespace cm --include-crds
```