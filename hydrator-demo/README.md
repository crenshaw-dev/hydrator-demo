
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/crenshaw-dev/hydrator-demo
# cd into the cloned directory
git checkout 8ec2b99bd51e041c11fbe51c6defef601b1313c1
helm template . --name-template prom --namespace cm --include-crds
```