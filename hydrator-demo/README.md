
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/crenshaw-dev/hydrator-demo
# cd into the cloned directory
git checkout db6e62bfcd9c91d7b4371bbdf17537a2669f0a8f
helm template . --name-template cm --namespace cm --include-crds
```