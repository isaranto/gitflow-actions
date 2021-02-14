# GitFlow Actions

A way to automate the gitflow release process using github actions for GitHub repositories.
More specifically the existing approach can be applied on repositories with branch protection rules where an approved Pull Request is required in order to merge a branch into either the develop or master branch.
It all starts with a version defined in the manifest file `package.json`

<img src="https://wac-cdn.atlassian.com/dam/jcr:61ccc620-5249-4338-be66-94d563f2843c/05%20(2).svg?cdnVersion=1454" alt="gitflow" width="800"/>

For more information regarding the GitFlow branching model visit the following links:
https://nvie.com/posts/a-successful-git-branching-model/

https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow
