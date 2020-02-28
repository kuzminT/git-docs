### Must read, usefool and interesting articles
- [GitHub Flow: рабочий процесс Гитхаба](https://habr.com/ru/post/189046/) - GitHub Flow, git practise and experience from github developers.
- [A successful Git branching model](https://nvie.com/posts/a-successful-git-branching-model/)
- [Gitflow Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)
- [Forking Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/forking-workflow)


### Some main concepts and ideas

**The overall flow of Gitflow is:**

+ A develop branch is created from master
+ A release branch is created from develop
+ Feature branches are created from develop
+ When a feature is complete it is merged into the develop branch
+ When the release branch is done it is merged into develop and master
+ If an issue in master is detected a hotfix branch is created from master
+ Once the hotfix is complete it is merged to both develop and master