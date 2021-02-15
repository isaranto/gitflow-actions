# GitFlow Actions

A way to automate the gitflow release process using github actions for GitHub repositories.
More specifically the existing approach can be applied on repositories with branch protection rules where an approved Pull Request is required in order to merge a branch into either the develop or master branch.
It all starts with a version defined in the manifest file `package.json`.

To use this you need:
- A GitHub account/bot that will approve the Pull Requests created by the actions. Add the Personal Access Token (PAT) for this account as a secret in the settings of your repository. (In this example it is `BOT_TOKEN`.



<img src="https://wac-cdn.atlassian.com/dam/jcr:61ccc620-5249-4338-be66-94d563f2843c/05%20(2).svg?cdnVersion=1454" alt="atlassian-gitflow-image" width="450"/>

For more information regarding the GitFlow branching model visit the following links:

https://nvie.com/posts/a-successful-git-branching-model/

https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow
