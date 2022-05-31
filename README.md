# test-placement

To test generatoring `Policies` and `Placements` run
`kustomize build --enable-alpha-plugins .`

This will produce the two `PlacementRules` in ./placements along with the output from the Policy Generator which does not include the referenced placements.

This will allow managaging the placement rules separate from the generated Policies.



