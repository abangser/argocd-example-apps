# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/abangser/argocd-example-apps
# cd into the cloned directory
git checkout 0f2ebdd0ea18e0ffdd9d9c3f1b2b2dd9ba8deaa9
helm template . --name-template staging-helm-guestbook --include-crds
```
