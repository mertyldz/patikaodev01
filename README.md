# What is **GIT** ?
*With Git, you can use a variety of branching strategies and workflows. Having a structured workflow for collaboration in complex projects is crucial for several reasons:*
* Code organization 
* Version control
* Code quality
* Traceability and accountability
* Easier onboarding
* Time and resource management
* CI/CD
# Gitflow
## Main Branches
At the core, the development model is greatly inspired by existing models out there. The central repo holds two main branches with an infinite lifetime:
* master
* develop
  
![MainBranch](https://nvie.com/img/main-branches@2x.png)
## Supporting Branches
Next to the main branches master and develop, our development model uses a variety of supporting branches to aid parallel development between team members, ease tracking of features, prepare for production releases and to assist in quickly fixing live production problems. Unlike the main branches, these branches always have a limited life time, since they will be removed eventually.

The different types of branches we may use are:
* **Feature branches** `git checkout -b myfeature develop`

![feature-branch](https://nvie.com/img/merge-without-ff@2x.png)
* **Release branches**
* **Hotfix branches**

![hotfix-branch](https://nvie.com/img/hotfix-branches@2x.png)

Check out these websites for more information:
1. https://docs.gitlab.com/ee/topics/gitlab_flow.html
2. https://nvie.com/posts/a-successful-git-branching-model/ 