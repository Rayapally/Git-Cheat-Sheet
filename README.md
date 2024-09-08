<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Git Cheat Sheet</title>
    
</head>
<body>
    <h1>Git Cheat Sheet</h1>
    <table>
        <thead>
            <tr>
                <th>Command</th>
                <th>Description</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>yum install git -y</td>
                <td>To install git in Linux machine</td>
            </tr>
            <tr>
                <td>git init .</td>
                <td>To initialize empty repo in current directory</td>
            </tr>
            <tr>
                <td>git config user.name "username"</td>
                <td>Configure username for Git</td>
            </tr>
            <tr>
                <td>git config user.email "email"</td>
                <td>Configure user email for Git</td>
            </tr>
            <tr>
                <td>git add filename</td>
                <td>Used to track a file</td>
            </tr>
            <tr>
                <td>git add *</td>
                <td>Track all files & folders</td>
            </tr>
            <tr>
                <td>git add .</td>
                <td>Track all files in current directory (including hidden files)</td>
            </tr>
            <tr>
                <td>git add -f filename</td>
                <td>Track files forcefully</td>
            </tr>
            <tr>
                <td>git rm --cached filename</td>
                <td>Untrack the file</td>
            </tr>
            <tr>
                <td>git commit -m "message" filename</td>
                <td>Commit a file with a message</td>
            </tr>
            <tr>
                <td>git commit -m "message" .</td>
                <td>Commit all files in the staging area with a message</td>
            </tr>
            <tr>
                <td>git log</td>
                <td>See the history of the repository</td>
            </tr>
            <tr>
                <td>git log --oneline</td>
                <td>See only commit IDs and messages</td>
            </tr>
            <tr>
                <td>git log -1</td>
                <td>See the latest commit</td>
            </tr>
            <tr>
                <td>git log -3</td>
                <td>See the latest 3 commits</td>
            </tr>
            <tr>
                <td>git log --follow --all filename</td>
                <td>See the number of commits for a single file</td>
            </tr>
            <tr>
                <td>git show commit_id --name-only</td>
                <td>See commit details along with file names</td>
            </tr>
            <tr>
                <td>git show commit_id --stat</td>
                <td>See the history of a file (modifications, data added, and deleted)</td>
            </tr>
            <tr>
                <td>git commit --amend -m "message"</td>
                <td>Change the commit message for the latest commit</td>
            </tr>
            <tr>
                <td>git commit --amend --author "username &lt;mail&gt;"</td>
                <td>Change the author of the latest commit</td>
            </tr>
            <tr>
                <td>git commit --amend --no-edit</td>
                <td>Commit the changes with the previous commit</td>
            </tr>
            <tr>
                <td>git reset --hard HEAD~1</td>
                <td>Delete the latest commit along with the changes</td>
            </tr>
            <tr>
                <td>git reset --hard HEAD~3</td>
                <td>Delete the latest 3 commits along with the changes</td>
            </tr>
            <tr>
                <td>git reset --soft HEAD~1</td>
                <td>Delete only commits but keep changes/actions</td>
            </tr>
            <tr>
                <td>git reset --soft HEAD~3</td>
                <td>Delete only the latest commits but keep changes/actions</td>
            </tr>
            <tr>
                <td>git revert commit_id</td>
                <td>Delete a particular commit action and add a new commit for the change</td>
            </tr>
            <tr>
                <td>git branch</td>
                <td>See the list of branches</td>
            </tr>
            <tr>
                <td>git branch branch-name</td>
                <td>Create a branch</td>
            </tr>
            <tr>
                <td>git checkout branch-name</td>
                <td>Switch from one branch to another</td>
            </tr>
            <tr>
                <td>git checkout -b branch-name</td>
                <td>Create and switch to a new branch at the same time</td>
            </tr>
            <tr>
                <td>git branch -m old-branch new-branch</td>
                <td>Rename a branch</td>
            </tr>
            <tr>
                <td>git branch -d branch-name</td>
                <td>Delete a branch</td>
            </tr>
            <tr>
                <td>git branch -D branch-name</td>
                <td>Forcefully delete a branch</td>
            </tr>
            <tr>
                <td>git merge branch</td>
                <td>Copy all commits from one branch to another</td>
            </tr>
            <tr>
                <td>git cherry-pick commit-id</td>
                <td>Copy a single commit from one branch to another</td>
            </tr>
            <tr>
                <td>git merge --abort</td>
                <td>Cancel the merge when conflicts arise</td>
            </tr>
            <tr>
                <td>git rebase branch</td>
                <td>Copy all commits from one branch to another</td>
            </tr>
            <tr>
                <td>git stash</td>
                <td>Delete the changes permanently</td>
            </tr>
            <tr>
                <td>git stash save "message"</td>
                <td>Save the stash along with a message</td>
            </tr>
            <tr>
                <td>git stash apply</td>
                <td>Retrieve the stashed changes</td>
            </tr>
            <tr>
                <td>git stash list</td>
                <td>Get the list of stashes</td>
            </tr>
            <tr>
                <td>git stash clear</td>
                <td>Clear all stashes</td>
            </tr>
            <tr>
                <td>git stash pop</td>
                <td>Delete the first stash</td>
            </tr>
            <tr>
                <td>git stash drop</td>
                <td>Delete the latest stash</td>
            </tr>
            <tr>
                <td>git stash drop stash@{2}</td>
                <td>Delete a particular stash</td>
            </tr>
            <tr>
                <td>git remote add origin repo-url</td>
                <td>Link local repo to central repo</td>
            </tr>
            <tr>
                <td>git push -u origin branch-name</td>
                <td>Push the code from local to central</td>
            </tr>
            <tr>
                <td>git push -u origin branch-1 branch-2</td>
                <td>Push the code to multiple branches</td>
            </tr>
            <tr>
                <td>git push -u origin --all</td>
                <td>Push the code to all branches at once</td>
            </tr>
            <tr>
                <td>git clone repo-url</td>
                <td>Get the code from central to local</td>
            </tr>
            <tr>
                <td>git pull origin branch</td>
                <td>Get changes from central to local</td>
            </tr>
            <tr>
                <td>git fetch branch-name</td>
                <td>Fetch the data from central to local</td>
            </tr>
            <tr>
                <td>git fetch --all</td>
                <td>Fetch changes from all branches in GitHub</td>
            </tr>
            <tr>
                <td>git merge origin/branch</td>
                <td>Merge the changes from central to local</td>
            </tr>
            <tr>
                <td>git push -u origin --delete branch-name</td>
                <td>Delete the GitHub branch from local</td>
            </tr>
            <tr>
                <td>git remote rm origin</td>
                <td>Unlink the GitHub repo</td>
            </tr>
            <tr>
                <td>git remote rename old-link new-link</td>
                <td>Change the repo link</td>
            </tr>
            <tr>
                <td>git remove -v</td>
                <td>View linked repositories</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
