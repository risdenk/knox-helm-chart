# knox-helm-chart

## Setup
* `brew install kubernetes-helm`
* `helm init`
* `helm repo update`

## Creating the Knox chart
* `helm create knox`
* `helm lint ./knox`
* `helm install --dry-run --debug ./knox`
* `helm install --name knox ./knox`
* `helm del --purge knox`

## References
* https://helm.sh/docs/using_helm/
* https://docs.bitnami.com/kubernetes/how-to/create-your-first-helm-chart/

