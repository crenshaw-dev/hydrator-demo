
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/crenshaw-dev/hydrator-demo
# cd into the cloned directory
git checkout 2f20f0d2ac06109b310985a0e546c391f8932f57
helm template . --name-template prom --namespace cm --include-crds
```