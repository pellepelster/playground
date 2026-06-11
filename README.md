# Playground

Playground for various infrastructure-stuff

## Bootstrap K8S cluster and install demo app

```shell
mise k3d:bootstrap
mise cnpg:operator:install
mise hello-world:apply
```
