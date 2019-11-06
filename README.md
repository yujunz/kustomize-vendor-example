# kustomize

## Install plugin

```sh
curl https://raw.githubusercontent.com/kubernetes-sigs/kustomize/master/plugin/someteam.example.com/v1/gogetter/GoGetter \
--create-dirs -o ~/.config/kustomize/plugin/someteam.example.com/v1/gogetter/GoGetter
```

## Vendor

```sh
kustomize build --enable_alpha_plugin vendor > vendor.yaml
```

## Build

```sh
kustomize build
```
