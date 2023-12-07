# GitHub Documentation
<sup>Note: If you are looking at this as reference for the USSTM Website, and you have not contributed since we migrated to NextJS, please delete your local repo and re-clone from GitHub.</sup>
This documentation assumes that you have the git CLI installed.

## Cloning a Repository
When contributing to a repository, we first want to clone it. To do so, follow these steps:
 - Open the repository on the GitHub website, and click on the `< > Code` green button.
 - Copy the link the is displayed.
 - Navigate to where you want to store your cloned repository.
 - Open your terminal/command prompt in this .
 - Type the following:
   ```
   git clone <LINK-YOU-COPIED>  
   ```
 - Type `ls` to find the exact name of the folder that was cloned (this will usually be the name of the GitHub repository.
 - Type the following two commands in your terminal/command prompt to open the cloned repository in Visual Studio Code:
   ```
   cd <CLONED-FOLDER>
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

