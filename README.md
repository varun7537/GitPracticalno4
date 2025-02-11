**1. Clone the Repository
You started by cloning a GitHub repository using the command:

git clone https://github.com/varun7537/GitPracticalno4.git
This command makes a copy of the repository from GitHub to your local machine.
After cloning, you entered the project directory GitPracticalno4 using cd GitPracticalno4.
2. Create a New Branch
You created a new branch for your feature development:


git checkout -b mynewgitbranch
git checkout -b mynewgitbranch creates a new branch called mynewgitbranch and switches to it.
This is where you will add your changes.
3. Create New Files
You created a few new files:


touch index.html
touch style.css
touch script.js
touch config.php
These commands create four new empty files in your project: index.html, style.css, script.js, and config.php.
4. Stage Your Changes
You staged the files to be committed using:


git add --all
This adds all the new files to the "staging area," meaning Git will now track the changes you've made.
5. Commit Your Changes
You made a commit with a message:


git commit -m "Describe your changes"
This saves your changes to the branch with the message "Describe your changes". Git records these changes as a snapshot in the history.
6. Push the Changes to GitHub
You attempted to push the branch to GitHub using:


git push origin mynewgitbranch
The first time you tried this, you encountered an authentication issue (Invalid username or password).
The issue might have been caused by an incorrect login or a need for GitHub authentication using a personal access token (PAT) instead of a password. This is a common issue when pushing to GitHub after the password authentication was deprecated.
After this, you successfully pushed your branch:


git push origin mynewgitbranch
This command pushes the changes in your mynewgitbranch to the remote repository on GitHub.


remote: Create a pull request for 'mynewgitbranch' on GitHub by visiting:
remote: https://github.com/varun7537/GitPracticalno4/pull/new/mynewgitbranch
This message lets you know that your branch is now on GitHub and you can create a pull request (PR) to merge it with the main branch.


7. Switch Back to the Main Branch
You switched back to the main branch using:


git checkout main
This command switches you back to the main branch from the feature branch (mynewgitbranch).
8. Pull Latest Changes
You then pulled the latest changes from GitHub to ensure your local main branch is up to date:


git pull origin main
This command fetches and merges any new changes from the remote main branch on GitHub to your local main branch.
Result
Now, your main branch is up-to-date with the changes from the mynewgitbranch you pushed earlier. Your files (index.html, style.css, script.js, config.php) are also in sync with the changes from your new branch.

Summary of What Happened:
You cloned the repository from GitHub.
You created a new branch called mynewgitbranch.
You added new files (index.html, style.css, script.js, config.php).
You staged and committed the changes.
You pushed the changes to GitHub.
You switched back to the main branch and pulled the latest changes.
Next Steps:
On GitHub, you can now create a Pull Request (PR) to merge your mynewgitbranch into the main branch. This allows teammates to review and approve the changes before they are merged into the main project.
Let me know if you need more help with any of these steps!**
