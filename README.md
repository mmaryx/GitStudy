# Git e GitHub - Notes

Hi! This is my Git and Github studies.

---------------------------------------------------------------------------

- What is Git? Git is a sistem of file versioning. Why using he?

    As an example I can use a client's project that had many changes. Traditionally, we would "zip" and send it to the client, as he asks for changes we will create more and more zipped folders. If the customer says that he wants something that you used in the first version, but that has already been excluded from your current version, to find that item, you would have to open folder by folder behind the item.

    With Git it's different. When the client approves a release, we don't generate a zip, we commit it to a local repository. And multiple people can also make these commits. After finishing a commit you push it to a remote repository. This way everyone who is part of the project can see your changes.

-benefits:

    * History Control

    * Team Work

    * Project Branching

    * Security

    * Organization

---------------------------------------------------------------------------

- What is GitHub? GitHub is a platform (software) for hosting git files, which works through a remote repository.

---------------------------------------------------------------------------

-benefits:

    * Unlimited Repositories

    * Source Code Hosting

    * Social Networking Features

    * Integrated GitHub Pages
    
    * Collaboration

    * Forks

---------------------------------------------------------------------------

# Vocabulário

 - Branch: are branches of the project. We can use it as a stub that doesn't change the master(or main) branch. They are used to separate major changes or new features of the project.

 - Commit: is a group of code changes. Every time you want to "save" the changes you made to the repository, you commit those changes.

 - Push: uploads the code to the online repository.

 - Merge:is the union of two branches. Typically, merges are done on the master branch.

 - Pull: it is an update from the local repository. The online repository is merged with the local one so that conflicts are resolved and it is possible to push the code (without conflicts) to the online repository via a push.

 - Fork: it's like a clone, but inside github. This means that the repository will not be downloaded to your computer, but an equal one will be created on your account.
 
 - Pull request:is a request made to the owner of the repository to update his code with your code.

 - Clone: works like a branch of an online repository into a local repository. That is, when you want to work on a repository hosted on github, you clone that repository to your computer, work on it, and then ask for permission to update the changes online.

---------------------------------------------------------------------------

# Basic Git Bach Commands

 - git --version (see the git version)
 - git init (initializes a git repository, already inside a master branch)
 - git add (adds an active directory change to the staging area)
 - git add . (adds all changes made to the working directory to the staging area)
 - git commit -m "..." (make a commit)
 - git branch -M "..." (change the branch name)
 - git push origin "nome da branch" (push your changes to the GitHub repository)
 - git checkout "nome da branch" (enter the chosen branch)
 - git merge "nome da branch" (join the chosen branch to the current one (main))

---------------------------------------------------------------------------

