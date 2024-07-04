CASE STUDY - GIT WORKFLOW
Problem Statement:
You work as a Devops Architect in Zendriix Softwares. The company has been struggling to
manage their product releases. The releases should happen on 25th of every month. Suggest a
Git Workflow Architecture for this requirement.
Simulate this workflow, by creating a pseudo code files and branches, and upload the same to
your GitHub Account.
As a part of solution, share the link to your GitHub repository.
Ans- 
Summary: Three separate branches “master”, “develop” & “feature” created. The “develop” branch will be created from the “master” branch, while the “feature” branch will be created from the “develop” branch. Three files such as “master.txt”, “develop.txt” & “feature.txt” in these respective branches has been created.

After creating all the branches & files, the “feature” branch into the “develop” branch & after merging the “feature” branch merged, later merged the “develop” branch into the “master” branch.

Merging all branches into a master means the final code is ready to release & company will easily release the final product on the 25th of every month using this strategy.
