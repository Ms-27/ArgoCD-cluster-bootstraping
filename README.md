# ArgoCD-cluster-bootstraping

`argocd app create appgroup --repo https://github.com/little-bear-creator/AppGroupe.git --path . --dest-namespace spring-apps-dev --dest-server https://kubernetes.default.svc --directory-recurse`