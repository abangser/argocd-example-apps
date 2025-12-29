# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/abangser/argocd-example-apps
# cd into the cloned directory
git checkout 81bc250cf4847a5e8fcbea1c4370771d27a7ddf9
helm template . --name-template development-helm-guestbook --include-crds
```
