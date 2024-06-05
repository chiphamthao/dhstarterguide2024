# dhstarterguide2024

**Quick Start**

You can refer to GitHub’s Quick Start [guide](https://docs.github.com/en/get-started/start-your-journey/hello-world) to learn about making a new repository, starting a new branch, creating and committing changes, and opening a pull request on GitHub

**Collaboration on GitHub**

Owner: To add collaborators to your repo, navigate to Settings > Collaborators > Add people

Collaborator: clone the project using the command `git clone project_URL`
Then, you can make changes to the project and commit those changes using the following commands:

1. `git branch -m branch_name`
2. `git status` (to see the changes you made)
3. `git add .` or `git add filename`
4. `git commit -m "commit_message"`
5. `git push -u origin branch_name `

Now, your changes are visible on branch_name on GitHub:

![alt text](<Screenshot 2024-06-05 at 11.52.26 PM.png>)

These changes are not yet merged into the main branch. You must click on "Compare and pull request" to create a pull request so that it can be reviewed by the owner of the repo:

![alt text](<Screenshot 2024-06-06 at 12.00.02 AM.png>)
