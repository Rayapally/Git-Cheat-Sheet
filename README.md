<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Git Cheat Sheet</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #f4f4f4;
        }
        code {
            background-color: #f9f9f9;
            padding: 2px 4px;
            border-radius: 4px;
        }
    </style>
</head>
<body>
    <h1>Git Cheat Sheet</h1>
    <table>
        <thead>
            <tr>
                <th>Commands</th>
                <th>Description</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><code>git init</code></td>
                <td>Initialize a new Git repository in the current directory</td>
            </tr>
            <tr>
                <td><code>git config user.name "username"</code></td>
                <td>Set the name for commits</td>
            </tr>
            <tr>
                <td><code>git config user.email "useremail"</code></td>
                <td>Set the email for commits</td>
            </tr>
            <tr>
                <td><code>git add filename</code></td>
                <td>Add a specific file to the staging area</td>
            </tr>
            <tr>
                <td><code>git add .</code></td>
                <td>Add all changes in the current directory to the staging area</td>
            </tr>
            <tr>
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
