# GIT-ASSIGNMENT
# Git Assignment - Building a branching model


<p align = "center">
Commits in Repository.

</p>
<img width="1440" alt="Screenshot 2023-01-26 at 1 36 39 AM" src="https://user-images.githubusercontent.com/122535424/214677831-337fd6f4-1ec6-4e2d-9a2d-3d1258070962.png">

5 Branches to be made
- Production (master)
- Integration
- HotFix 
- Feature1 
- Feature2
#### Step - 1
- Start with the Production branch (master branch), and then create a HotFix and Integration branch.
#### Step - 2
- Subsequently, create Feature 1 and 2 branches that integrate to the Integration branch as shown in the above figure
#### Step - 3
- Commit some changes in the Feature 2 branch and Create Pull Request, add 2 reviewers, get the PR reviewed & merge it into the Integration branch. Delete this branch once merging is complete
#### Step - 4
- Commit some changes in the Feature 1 branch and rebase it to the Integration branch
#### Step - 5
- Create Pull Request, add 2 reviewers, get the PR reviewed & Merge the Integration branch
into Hotfix and Production branch to update these branches
#### Step - 6
- Commit some changes in Feature 1 branch, and then Create Pull Request, add 2 reviewers,
get the PR reviewed & merge it into Integration, Hotfix, and Production branch. Delete this
branch once merging is complete
#### Step - 6
Commit some changes in the Hotfix branch and Create Pull Request, add 2 reviewers, get
the PR reviewed & merge it into the Production as well as the Integration branch
### Common Commands Used - 
- `git clone` - To clone the repository
- `git log --online` - To view the current logs graph for the repository
- `git push` - To push the local changes onto origin
- `git pull` - To pull changes from origin to local git pull
- `git checkout` - To navigate between the branches created by git branch git checkout 
- `git branch` - To create or delete branches: git branch
- `git checkout -d [branch name]` - To delete a particular branch git checkout -d [branch name]
- `git checkout -b [branch name]` - To switch in a branch or create then switch to that branch if it doesn't exist git checkout -b [branch name]
