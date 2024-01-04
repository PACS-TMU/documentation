# GitHub Documentation
<sup>Note: If you are looking at this as reference for the USSTM Website, and you have not contributed since we migrated to NextJS, please delete your local repo and re-clone from GitHub.</sup> <br />
This documentation assumes that you have the git CLI installed.

## Cloning a Repository
When contributing to a repository, we first want to clone it. To do so, follow these steps:
 - Open the repository on the GitHub website, and click on the `< > Code` green button.
 - Copy the link the is displayed.
 - Navigate to where you want to store your cloned repository.
 - Open your terminal/command prompt in this path.
 - Type the following:
   ```
   git clone <LINK-YOU-COPIED>  
   ```
 - Type `ls` to find the exact name of the folder that was cloned (this will usually be the name of the GitHub repository.
 - Type the following two commands in your terminal/command prompt to open the cloned repository in Visual Studio Code:

   ```
   cd <CLONED-FOLDER>
   ```
 - Next, open the directory you have navigated to with your previous command in your preferred IDE (Visual Studio Code is recommended for website development). This can be acheived by opening VSCode then navigating to `file`>`open folder` and then double click the website folder you cloned. Another way this could be achieved is by running the following in your terminal after you executed the `cd` command outlined in the previous step:

   ```
   code .
   ```
   
  - Now you can make changes to the cloned repository

## Making Changes and Pushing to GitHub Repository

### Pulling Changes
After you clone, you can make changes. It is important to keep your local repository clone up-to-date with the GitHub repository. To do that, run the following command regularly (e.g., at the beginning of each session):

```
git pull
```

### Branches
When being assigned a ticket, you will likely be asked to work in a seperate branch. To do so, you can either create a branch from your assigned issue, or you can run the following command in the terminal in your project directory:

```
git checkout -b <NEW-BRANCH-NAME>
```

To check which branch you are on, you can run the following command:

```
git status
```

Ensure that you are on the correct branch before adding and committing changes.

### Adding, Committing and Pushing Changes
After making all your changes, run:
```
git status
```

After you ensure you are on the correct branch, run the following commands, in order:
```
git add .
git commit -m "COMMIT MESSAGE"
git push
```

For your commit message, please make it a good balance between descriptive and short to tell us what changes you made to the code.

When pushing for the first time, you might have to set your branch as the upstream branch (you will get an warning message, and your push would not be successful). This is because the branch you created is not yet up on GitHub (until you push for the first time). To solve this issue, you can run the following command instead of `git push`:
```
git push --set-upstream origin <NEW-BRANCH-NAME>
```
Note that you will only have to do this the first time you push from your new branch, and not constantly.

The branch you are working on will now have all the updates on the GitHub website. To merge it to the dev/main branch, you need to make a pull request.

## Making a Pull Request
To make a pull request, open the GitHub repository you made changes in and follow these steps:
- Press `Pull Requests` from the top menu
- Press `New Pull Request` (a green button on the top right corner)
- For the branches, the `base: <branch-name>` should be the branch you want to merge into (usually dev/main) and the `compare: <branch-name>` would be the branch you pushed your changes to.
- Once you select your branches, press `Create pull request`
- Add a title and description to tell us what changes you made and are merging
- Press `Create Pull Request` below the description section
- Request reviewers from the side menu, if necessary
