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

## Create Helm package
* `helm package ./knox`
* `helm repo index .`

## Add chart to Helm
* `helm repo add knox 'https://raw.githubusercontent.com/risdenk/knox-helm-chart/master/'`
* `helm repo update`
* `helm search knox`

## References
* https://helm.sh/docs/using_helm/
* https://docs.bitnami.com/kubernetes/how-to/create-your-first-helm-chart/
* https://hackernoon.com/using-a-private-github-repo-as-helm-chart-repo-https-access-95629b2af27c

