# Github_actions_CI_CD_integration
Github action CI CD pipeline integration
Steps to create a workflow:-
    1. Create a folder name .github
    2. Create a folder name workflows inside .github folder.
    3. Inside the folder workflows created a yml file which triggers the workflow actions when we push some code in our main or prod branch.
Added another workflow named as - all branch workflow:- it will trigger when any push done from any branch to repository.

Added multi event workflow named as - multi event pipeline :- 
        1. push event will trigger the job on-push when we push our code through master branch.
        2. pull_request will trigger the job on-pull_request when we do pull request on main branch.