<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    
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
                <td><code>git init .</code></td>
                <td>Initialize a new Git repository in the current directory</td>
            </tr>
            <tr>
                <td><code>git config user.name "username"</code></td>
                <td>used to configure user name for our git</td>
            </tr>
            <tr>
                <td><code>git config user.email "useremail"</code></td>
                <td>used to configure user email for our git</td>
            </tr>
            <tr>
                <td><code>git add filename</code></td>
                <td>Used to track a file name</td>
            </tr>
            <tr>
                <td><code> git add * </code></td>
                <td><code> used to track all files & folders </code></td>
                </tr>
            <tr>
                <td><code>git add .</code></td>
                <td>used to track all files in current directory (including hidden files)</td>
            </tr>
            <tr>
                <td><code>git add -f filename</code></td>
                <td>to track files forcefully</td>
            </tr>
            <tr>
                <td><code>git rm --cached filename</code></td>
                <td>used to untrack the file</td>
            </tr>
            <tr>
                <td><code>git commit -m "message" filename</code></td>
                <td>to commit a file</td>
            </tr>
            <tr>
                <td><code>git commit -m "message" .</code></td>
                <td>used to commit all files which are present in staging area</td>
            </tr>
            <tr>
                <td><code>git log</code></td>
                <td>used to see the history of the git</td>
            </tr>
            <tr>
                <td><code>git log --oneline</code></td>
                <td>used to see only commit ID's and messages</td>
            </tr>
            <tr>
                <td><code>git log --follow --all filename</code></td>
                <td>used to see the no of commits for a single file</td>
            </tr>

            <!-- Add more rows as needed -->
        </tbody>
    </table>
</body>
</html>
