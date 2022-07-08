# Git-test

new_commit_654

Summary
Here we discussed the Gitflow Workflow. Gitflow is one of many styles of Git workflows you and your team can utilize.

Some key takeaways to know about Gitflow are:

The workflow is great for a release-based software workflow.
Gitflow offers a dedicated channel for hotfixes to production.
 
The overall flow of Gitflow is:

A develop branch is created from main
A release branch is created from develop
Feature branches are created from develop
When a feature is complete it is merged into the develop branch
When the release branch is done it is merged into develop and main
If an issue in main is detected a hotfix branch is created from main
Once the hotfix is complete it is merged to both develop and main
