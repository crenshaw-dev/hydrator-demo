
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/crenshaw-dev/hydrator-demo
# cd into the cloned directory
git checkout a19629b347f56ed61f4dd71e82daefe65e172424
helm template . --name-template prom --namespace prom --include-crds
```