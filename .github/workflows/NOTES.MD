# Some Notes On Each Option


## 03-ci-cd-reusable-wf.yml
#### Pros
- nice single pipeline build -> deploy view
- 
#### Cons
- can't deploy infra without a rebuild
- can manually trigger deploy to specific environments




## Regional Deployment and Environments using Matrix
- To fully leverage environments in a matrix deployment setup, we'd need to setup an Env per Region. e.g. Prod-AU, Prod-EU, Prod-CA


