
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/crenshaw-dev/hydrator-demo
# cd into the cloned directory
git checkout c38adfcc0aaa829115693a7e60220f42925c03f3
helm template . --name-template prom --namespace prom --include-crds
```