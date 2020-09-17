# ci

Blockchain Exchange CI

The CI pipeline in StackStorm Exchange is based on CircleCI 
(see .circle/circle.yml.sample for the reference config). 

On every PR we automatically run tests (if present), 
check the pack config schemas, perform code style checks, 
and validate pack.yaml.
