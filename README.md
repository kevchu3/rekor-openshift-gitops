# Rekor ArgoCD Deployment on OpenShift

This ArgoCD application wraps the deployment of the [sigstore Rekor Helm chart](https://github.com/sigstore/helm-charts/tree/main/charts/rekor) with Kustomization of additional resources to deploy to Red Hat OpenShift.  The [values.yaml](base/values.yaml) file can be customized further as documented [here](https://github.com/sigstore/helm-charts/blob/main/charts/rekor/values.yaml).

Deploy ArgoCD application:
```
$ oc apply -f rekor.application.yaml
```
