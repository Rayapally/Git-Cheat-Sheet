<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Git Commands Reference</title>
</head>
<body>
    <h1>Git Commands Reference</h1>
    <table border="1" cellpadding="10" cellspacing="0">
        <thead>
            <tr>
                <th>Command</th>
                <th>Description</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><code>git branch -d branch-name</code></td>
                <td>Delete a branch (only if it has been fully merged).</td>
            </tr>
            <tr>
                <td><code>git branch -D branch-name</code></td>
                <td>Forcefully delete a branch (even if it hasn’t been merged).</td>
            </tr>
            <tr>
                <td><code>git branch</code></td>
                <td>List all branches.</td>
            </tr>
            <tr>
                <td><code>git branch branch-name</code></td>
                <td>Create a new branch.</td>
            </tr>
            <tr>
                <td><code>git branch -m old-branch new-branch</code></td>
                <td>Rename a branch.</td>
            </tr>
            <tr>
                <td><code>git checkout branch-name</code></td>
                <td>Switch to a branch.</td>
            </tr>
            <tr>
                <td><code>git checkout -b branch-name</code></td>
                <td>Create and switch to a new branch.</td>
            </tr>
            <tr>
                <td><code>git merge branch</code></td>
                <td>Merge the specified branch into the current branch.</td>
            </tr>
            <tr>
                <td><code>git merge --abort</code></td>
                <td>Abort the current merge process.</td>
            </tr>
            <tr>
                <td><code>git rebase branch</code></td>
                <td>Rebase the current branch onto the specified branch.</td>
            </tr>
            <tr>
                <td><code>git cherry-pick commit-id</code></td>
                <td>Apply the changes introduced by a specific commit from another branch.</td>
            </tr>
            <tr>
                <td><code>git revert commit-id</code></td>
                <td>Create a new commit that undoes the changes of a specific commit.</td>
            </tr>
            <tr>
                <td><code>git stash</code></td>
                <td>Stash the current changes in a working directory.</td>
            </tr>
            <tr>
                <td><code>git stash save "message"</code></td>
                <td>Stash the current changes with a descriptive message.</td>
            </tr>
            <tr>
                <td><code>git stash apply</code></td>
                <td>Apply the most recent stash without removing it from the stash list.</td>
            </tr>
            <tr>
                <td><code>git stash list</code></td>
                <td>List all stashes.</td>
            </tr>
            <tr>
                <td><code>git stash clear</code></td>
                <td>Remove all stashes.</td>
            </tr>
            <tr>
                <td><code>git stash pop</code></td>
                <td>Apply the most recent stash and remove it from the stash list.</td>
            </tr>
            <tr>
                <td><code>git stash drop</code></td>
                <td>Remove the most recent stash.</td>
            </tr>
            <tr>
                <td><code>git stash drop stash@{2}</code></td>
                <td>Remove a specific stash.</td>
            </tr>
            <tr>
                <td><code>git remote add origin repo-url</code></td>
                <td>Link a local repository to a remote repository.</td>
            </tr>
            <tr>
                <td><code>git push -u origin branch-name</code></td>
                <td>Push the local branch to the remote repository.</td>
            </tr>
            <tr>
                <td><code>git push -u origin branch-1 branch-2</code></td>
                <td>Push multiple branches to the remote repository.</td>
            </tr>
            <tr>
                <td><code>git push -u origin --all</code></td>
                <td>Push all branches to the remote repository.</td>
            </tr>
            <tr>
                <td><code>git clone repo-url</code></td>
                <td>Clone a remote repository to the local machine.</td>
            </tr>
            <tr>
                <td><code>git pull origin branch</code></td>
                <td>Fetch changes from the remote branch and merge them into the local branch.</td>
            </tr>
            <tr>
                <td><code>git fetch branch-name</code></td>
                <td>Fetch the latest changes from a specific branch.</td>
            </tr>
            <tr>
                <td><code>git fetch --all</code></td>
                <td>Fetch changes from all branches.</td>
            </tr>
            <tr>
                <td><code>git merge origin/branch</code></td>
                <td>Merge changes from the remote branch into the local branch.</td>
            </tr>
            <tr>
                <td><code>git push -u origin --delete branch-name</code></td>
                <td>Delete a branch from the remote repository.</td>
            </tr>
            <tr>
                <td><code>git remote rm origin</code></td>
                <td>Remove the remote repository configuration.</td>
            </tr>
            <tr>
                <td><code>git remote rename old-link new-link</code></td>
                <td>Rename a remote link.</td>
            </tr>
            <tr>
                <td><code>yum install git -y</code></td>
                <td>Install Git on a Linux machine using <code>yum</code>.</td>
            </tr>
            <tr>
                <td><code>git init</code></td>
                <td>Initialize an empty Git repository in the current directory.</td>
            </tr>
            <tr>
                <td><code>git config user.name "username"</code></td>
                <td>Set the username for commits.</td>
            </tr>
            <tr>
                <td><code>git config user.email "email"</code></td>
                <td>Set the email for commits.</td>
            </tr>
            <tr>
                <td><code>git add filename</code></td>
                <td>Stage a specific file for commit.</td>
            </tr>
            <tr>
                <td><code>git add *</code></td>
                <td>Stage all files and folders (excluding hidden files).</td>
            </tr>
            <tr>
                <td><code>git add .</code></td>
                <td>Stage all files in the current directory (including hidden files).</td>
            </tr>
            <tr>
                <td><code>git add -f filename</code></td>
                <td>Forcefully add a file.</td>
            </tr>
            <tr>
                <td><code>git rm --cached filename</code></td>
                <td>Unstage a file.</td>
            </tr>
            <tr>
                <td><code>git commit -m "message"</code></td>
                <td>Commit staged changes with a message.</td>
            </tr>
            <tr>
                <td><code>git commit -m "message" filename</code></td>
                <td>Commit a specific file with a message.</td>
            </tr>
            <tr>
                <td><code>git commit --amend -m "message"</code></td>
                <td>Amend the most recent commit with a new message.</td>
            </tr>
            <tr>
                <td><code>git commit --amend --author "username &lt;email&gt;"</code></td>
                <td>Amend the most recent commit with a new author.</td>
            </tr>
            <tr>
                <td><code>git commit --amend --no-edit</code></td>
                <td>Amend the most recent commit without changing the commit message.</td>
            </tr>
            <tr>
                <td><code>git reset --hard HEAD~1</code></td>
                <td>Remove the most recent commit and discard changes.</td>
            </tr>
            <tr>
                <td><code>git reset --hard HEAD~3</code></td>
                <td>Remove the last three commits and discard changes.</td>
            </tr>
            <tr>
                <td><code>git reset --soft HEAD~1</code></td>
                <td>Remove the most recent commit but keep the changes
