### Useful command

* flux get kustomization --watch

* flux diff kustomization flux-system --path clusters/GitOpsDemoCluster/

* flux reconcile kustomization flux-system with-source

* kubectl get kustomization -A

### Diagram

![Aks GitOps with Flux](aks-gitops.png)

## Reference:
https://techcommunity.microsoft.com/t5/azure-global/gitops-and-secret-management-with-aks-flux-cd-sops-and-azure-key/ba-p/2280068