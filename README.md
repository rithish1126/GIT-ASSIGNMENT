# GIT-ASSIGNMENT
# Git Assignment - Building a branching model


<p align = "center">
Fig.1 - History of Commits in my Repository.

</p>
<img width="1440" alt="Screenshot 2023-01-26 at 1 36 39 AM" src="https://user-images.githubusercontent.com/122535424/214677831-337fd6f4-1ec6-4e2d-9a2d-3d1258070962.png">

It contains 5 Branches - 
- Production (master)
- Integration
- HotFix 
- Feature1 
- Feature2
#### Step - 1
- I set up the Github repository and cloned it locally. then after that, Main Branch, a branching off of HotFix and Integration Branch, was developed.
#### Step - 2
- Making Feature1 and Feature2 Branches from the Integration Branch. Adding some changes then adding 2 reviewers Who made merging the pull request to integration.
#### Step - 3
- Change and commit in Feature1 in Local Environment. However, we now seek to act before the merge that occurred in the origin/Feature2 Therefore, we run the `git pull —rebase` command to rebase. This means that when we pull from the remote, our local commit will come first.
#### Step - 4
- Production(main) and HotFix branches now include changes from the Integration branch.
#### Step - 5
- Changes was developed on the HotFix branch and integrated into the Integration and Production branch.
#### Step - 6
- Feature1, Feature2, and HotFix branches were ultimately deleted after completing the aforementioned processes.
### Commands - 
- `git clone` - To clone the repository
- `git log --online` - To view the current logs graph for the repository
- `git push` - To push the local changes onto origin
- `git pull` - To pull changes from origin to local git pull
- `git checkout` - To navigate between the branches created by git branch git checkout 
- `git branch` - To create or delete branches: git branch
- `git checkout -d [branch name]` - To delete a particular branch git checkout -d [branch name]
- `git checkout -b [branch name]` - To switch in a branch or create then switch to that branch if it doesn't exist git checkout -b [branch name]
