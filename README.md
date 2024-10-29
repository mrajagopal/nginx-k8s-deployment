# nginx-k8s-deployment

## cm-nginx-conf.yaml
Generate one using existing `nginx.conf`: `kubectl create configmap nginx-config --from-file=nginx.conf`

## cm-nplusapi.yaml
Generate one using existing `NplusApi.conf`: `kubectl create configmap nplus-config --from-file=NplusApi.conf`
