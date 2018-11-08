# HOWTO

To update the repo with a new chart:

1. In this directory:

```
helm package $PATH_TO_CHART
helm repo index .
```

2. Commit the update.

# CONTENTS

- `alb-ingress-controller-helm` from https://github.com/kubernetes-sigs/aws-alb-ingress-controller/tree/master/alb-ingress-controller-helm
- `coreplane-alb-ingress-singleton` from https://github.com/coreplane/coreplane-infra (private)
- `kubernetes-dashboard` from
  https://github.com/coreplane/kubernetes-charts (modified fork of https://github.com/kubernetes/charts)
