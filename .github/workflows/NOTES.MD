# Some Notes On Each Option


## 03-ci-cd-reusable-wf.yml
#### Pros
- nice single pipeline build -> deploy view
- 
#### Cons
- can't deploy updates to infra without a rebuild
- can manually trigger deploy to specific environments
- can't rerun a called workflow, have to rerun jobs within the called workflow. When using matrix with dependencies between plan and apply, re-running deploy for a job



## Regional Deployment and Environments using Matrix
- To fully leverage environments in a matrix deployment setup, we'd need to setup an Env per Region. e.g. Prod-AU, Prod-EU, Prod-CA
- Or we put a bogus step before the regional deployments and put approval on it. 

