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
        <td><code>yum install git -y</code></td>
        <td>Install Git on Linux (package manager)</td>
      </tr>
      <tr>
        <td><code>git init .</code></td>
        <td>Initialize an empty Git repository in the current directory</td>
      </tr>
      <tr>
        <td><code>git config user.name "username"</code></td>
        <td>Configure user name for commits</td>
      </tr>
      <tr>
        <td><code>git config user.email "email"</code></td>
        <td>Configure user email for commits</td>
      </tr>
<tr>
        <td><code>git add filename</code></td>
        <td>Add a specific file to the staging area</td>
      </tr>
      <tr>
        <td><code>git add *</code></td>
        <td>Add all files and folders in the current directory to the staging area</td>
      </tr>
      <tr>
        <td><code>git add .</code></td>
        <td>Add all files (including hidden files) in the current directory to the staging area</td>
      </tr>
      <tr>
        <td><code>git add -f filename</code></td>
        <td>Track a file forcefully, even if it has issues</td>
      </tr>
      <tr>
        <td><code>git rm --cached filename</code></td>
        <td>Untrack a file from the staging area (but keep it in the working directory)</td>
      </tr>
        <tr>
        <td><code>git commit -m "message" filename</code></td>
        <td>Commit staged changes with a message, including a specific file</td>
      </tr>
      <tr>
        <td><code>git commit -m "message" .</code></td>
        <td>Commit all tracked changes with a message</td>
      </tr>
        <tr>
        <td><code>git log</code></td>
        <td>View commit history</td>
      </tr>
      <tr>
        <td><code>git log --oneline</code></td>
        <td>View commit history with one line per commit</td>
      </tr>
      <tr>
        <td><code>git log -1</code></td>
        <td>View the latest commit</td>
      </tr>
      <tr>
        <td><code>git log -3</code></td>
        <td>View the latest 3 commits</td>
      </tr>
      <tr>
        <td><code>git log --follow --all filename</code></td>
        <td>View the history of a specific file (including renames)</td>
      </tr>
      <tr>
        <td><code>git show commit_id --name-only</code></td>
        <td>Show all commit details with file names</td>
      </tr>
      <tr>
        <td><code>git show commit_id --stat</code></td>
        <td>See the history of a file (modifications, additions, deletions)</td>
      </tr>
        <tr>
        <td><code>git commit --amend -m "message"</code></td>
        <td>Change the commit message for the latest commit</td>
      </tr>
      <tr>
        <td><code>git commit --amend --author "username &lt;email&gt;"</code></td>
        <td>Change the author of the latest commit</td>
      </tr>
      <tr>
        <td><code>git commit --amend --no-edit</code></td>
        <td>Commit changes with the previous commit message</td>
      </tr>
        <tr>
        <td><code>git reset --hard HEAD~1</code></td>
        <td>Delete the latest commit along with changes (use with caution)</td>
      </tr>
      <tr>
        <td><code>git reset --hard HEAD~3</code></td>
        <td>Delete the latest 3 commits along with changes (use with caution)</td>
      </tr>
      <tr>
        <td><code>git reset --
                <td><code>git add -A</code></td>
                <td>Add all changes (including deletions) to the staging area</td>
            </tr>
            <tr>
                <td><code>git add -p</code></td>
                <td>Add changes in patches (interactive staging)</td>
            </tr>
            <tr>
                <td><code>git rm filename</code></td>
                <td>Remove a file from the working directory and the index</td>
            </tr>
            <tr>
                <td><code>git rm --cached filename</code></td>
                <td>Untrack a file but keep it in the working directory</td>
            </tr>
            <tr>
                <td><code>git commit -m "message"</code></td>
                <td>Commit staged changes with a message</td>
            </tr>
            <tr>
                <td><code>git commit -a -m "message"</code></td>
                <td>Commit all tracked changes with a message</td>
            </tr>
            <tr>
                <td><code>git log</code></td>
                <td>View commit history</td>
            </tr>
            <tr>
                <td><code>git log --oneline</code></td>
                <td>View commit history with one line per commit</td>
            </tr>
            <tr>
                <td><code>git log --graph</code></td>
                <td>View commit history with a graphical representation</td>
            </tr>
            <tr>
                <td><code>git status</code></td>
                <td>Check the status of the working directory and staging area</td>
            </tr>
            <tr>
                <td><code>git diff</code></td>
                <td>Show changes between working directory and the index</td>
            </tr>
            <tr>
                <td><code>git diff --cached</code></td>
                <td>Show changes between the index and the last commit</td>
            </tr>
            <tr>
                <td><code>git branch</code></td>
                <td>List all local branches</td>
            </tr>
            <tr>
                <td><code>git branch branch-name</code></td>
                <td>Create a new branch</td>
            </tr>
            <tr>
                <td><code>git checkout branch-name</code></td>
                <td>Switch to a different branch</td>
            </tr>
            <tr>
                <td><code>git checkout -b branch-name</code></td>
                <td>Create and switch to a new branch</td>
            </tr>
            <tr>
                <td><code>git merge branch-name</code></td>
                <td>Merge a branch into the current branch</td>
            </tr>
            <tr>
                <td><code>git rebase branch-name</code></td>
                <td>Rebase the current branch onto another branch</td>
            </tr>
            <tr>
                <td><code>git fetch</code></td>
                <td>Fetch changes from a remote repository</td>
            </tr>
            <tr>
                <td><code>git pull</code></td>
                <td>Fetch and merge changes from a remote repository</td>
            </tr>
            <tr>
                <td><code>git push</code></td>
                <td>Push local changes to a remote repository</td>
            </tr>
            <tr>
                <td><code>git remote -v</code></td>
                <td>List remote repositories</td>
            </tr>
            <tr>
                <td><code>git remote add origin url</code></td>
                <td>Add a remote repository</td>
            </tr>
            <tr>
                <td><code>git tag</code></td>
                <td>List all tags</td>
            </tr>
            <tr>
                <td><code>git tag tag-name</code></td>
                <td>Create a new tag</td>
            </tr>
            <tr>
                <td><code>git tag -d tag-name</code></td>
                <td>Delete a tag</td>
            </tr>
            <tr>
                <td><code>git stash</code></td>
                <td>Stash changes in a dirty working directory</td>
            </tr>
            <tr>
                <td><code>git stash apply</code></td>
                <td>Apply stashed changes</td>
            </tr>
            <tr>
                <td><code>git stash drop</code></td>
                <td>Remove a stash entry</td>
            </tr>
            <tr>
                <td><code>git reset</code></td>
                <td>Unstage changes or reset the index</td>
            </tr>
            <tr>
                <td><code>git reset --hard</code></td>
                <td>Reset the working directory and index to the last commit</td>
            </tr>
            <tr>
                <td><code>git revert commit-id</code></td>
                <td>Revert a specific commit</td>
            </tr>
            <tr>
                <td><code>git cherry-pick commit-id</code></td>
                <td>Apply the changes from a specific commit</td>
            </tr>
            <tr>
                <td><code>git bisect</code></td>
                <td>Find which commit introduced a bug by binary search</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
