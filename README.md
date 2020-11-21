# simple-samba-shares-helm

![Release Charts](https://github.com/pedrohdz/simple-samba-shares-helm/workflows/Release%20Charts/badge.svg?branch=master)

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
