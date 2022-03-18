# Tyro

userに該当するリソースはない

```shell
kubectl config set-credentials drogo --client-key=drogo.key --client-certificate=drogo.crt

kubectl config set-context developer --cluster=kubernetes --user=drogo

kubectl config use-context developer
```
