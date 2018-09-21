# DNP Exercises - Version Control

## Exercise 1

Install Git on your computer. Configure a username and email so that other Git collaborators can identify you.

Create a new Github account (or log in to an existing one). On your Github account, create a new online repository (do NOT initialize it with a README or .gitignore file).

## Exercise 2

Open a command prompt in a folder on your computer. Turn the directory into a Git repository by initializing a new, empty git repository in this folder. Add a README.md file with some content to your local repository. Commit the file with git commit. Add the remote GitHub repository to your local repository. Finally, push your local changes to the remote repository.

*Consider:*

- *"git remote add ..." is used to add a connection to a new remote repository.*
- *What is the difference between a commit and a push?*
- *After completing this exercise, what do you expect to see when you browse to your online GitHub repository that you created in exercise 1?*

## Exercise 3

Edit a file directly in your remote repository through the GitHub web interface. After having made the change on the Github web interface, use git log to compare your local repository history with the remote one on Github. You should have one fewer commit in your local repository. Pull the changes that your local repository is missing from your remote repository.

*Consider:*

- *Making commits manually this way is not best practice, and you should always work locally on a project and then push the changes to the remote repository. This trick simply lets us simulate commits being made on the remote repository but not in the local repository.*
- *If you have more than one computer you can try committing and pushing changes from one local repository (on computer A) and onto the remote and then pull the changes down to another local repository (on computer B).*

## Exercise 4

Using the same repository, make some changes to the local repository. Next, make some different changes to the remote repository. Commit the changes to both the local and remote repository. Try pushing your local changes to the remote repository which now contains its own changes. What happens? Find a way to synchronize the two repositories.

*Consider:*

- *Git fetch and git merge might come in handy here.*
- *If you aren’t expecting any merge conflicts, you can simply use git pull to retrieve the remote repo changes and merge them with your local repository.*
- *Try introducing a merge conflict by editing a line in the same file in both the local and remote repository (have the line say something different in each repository). Then try synchronizing the two repositories by solving the merge conflict.*

## Exercise 5

Clone this remote repository to your local machine (yes, the exercises themselves are actually a repository!). The repository should be cloned with a new name: “DNPisKing”. Next, display all of the commits of the repository in a terminal, each commit being on a single line. Make changes to the README.cd file and add a few new files. Commit all changes at once and try pushing them to the remote repo. What happens? Create a new GitHub repository and push your changes to this remote instead.

*Consider:*

- *The “git remote set-url” command can be used to change an existing repository url.*
- *You can confirm that the remote has been changed successfully by using the command “git remote -v”*

## Exercise 6

Initialize a new git repository in an empty folder. Add a README.md file to this repository with the contents “this is the master branch”. Add and commit the changes to the repository. Next, create a new branch for this repository called “testing”. Change the working directory to use this new branch. Change the README.md file to say “this is the testing branch”. Add and commit these changes. Return to the master-branch and have a look at the contents of the README.md file.

*Consider:*

- *The [git branch](https://git-scm.com/docs/git-branch) and [git checkout](https://git-scm.com/docs/git-checkout) commands might come in handy here.*
- *What happens to the contents of README.md file as you change branches?*
- *When is branching best used?*
- *Not sure why branching is smart? Check out [this short video guide](https://www.youtube.com/watch?v=JTE2Fn_sCZs)*
- *Use git status if you are not sure on what branch you currently are.*

## Exercise 7

Create an online repository (on GitHub) for your SEP3-project. Invite the other group members to collaborate with you on the project (so that they can make changes to the remote repository). Any members that you share the project with should have their own local repository using the same remote. For now, the repository will not contain any code, but you can start filling out the README file with information relevant to your project.