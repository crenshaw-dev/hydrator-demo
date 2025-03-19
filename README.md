
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/crenshaw-dev/hydrator-demo
# cd into the cloned directory
git checkout 1a13551040a00a875383c3a0cedad0e09fd85ab4
helm template . --name-template prom --include-crds
```