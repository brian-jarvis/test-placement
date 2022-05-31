# test-placement

To test generatoring placements run
`kustomize build --enable-alpha-plugins ./operators/`

This will produce error:
>Error: accumulating resources: accumulation err='accumulating resources from 'wookie/': '/var/home/bjarvis/src/acm-gitops/test-placement/operators/wookie' must resolve to a file': recursed merging from path '/var/home/bjarvis/src/acm-gitops/test-placement/operators/wookie': may not add resource with an already registered id: PlacementRule.v1.apps.open-cluster-management.io/dev.wookie-policies
