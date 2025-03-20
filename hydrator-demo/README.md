
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/crenshaw-dev/hydrator-demo
# cd into the cloned directory
git checkout 0738fd2be6f11e0b501a0f4cf76e258879ca68e5
helm template . --name-template cm --namespace cm --include-crds
```