# simple-samba-shares-helm

TODO

```bash
kubectl create namespace smb-test
kubens smb-test

kubectl apply -f ./test/k8s-test-resources.yaml
helm install --wait --values=test/helm-test-values.yaml foo .
```

```bash
helm uninstall foo
kubectl delete -f ./test/k8s-test-resources.yaml
kubectl delete namespace smb-test
kubens default
```


## TODO

- Add CI checks (linting, testing).
