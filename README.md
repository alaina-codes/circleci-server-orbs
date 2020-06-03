# CircleCI Server Orbs

Internal CircleCI Orbs for Rocket Mortgage Technology.


## Instructions

Publishing a new version:
```
circleci config pack $orb_dir > $orb_dir/orb.yml

circleci orb validate $orb_dir/orb.yml

# Dev version
circleci orb publish $orb_dir/orb.yml $namespace/$orb@dev:alpha

```