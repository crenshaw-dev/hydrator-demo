
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/crenshaw-dev/hydrator-demo
# cd into the cloned directory
git checkout f039913ed36c62693a9c0721dc6db9843baa7f25
helm template . --name-template prom --namespace prom --include-crds
```