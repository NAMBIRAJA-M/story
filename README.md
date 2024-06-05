

Creating and Managing a Git Repository

Creating a Directory and Adding Files:

The project starts by creating a new directory, which acts as a container for all project files. For example, using the command mkdir my_project, a directory named my_project is created. Within this directory, a file such as README.md is created to provide essential information about the project. Content is added to this file using simple text-writing commands.

Initializing a Git Repository:

Initializing a Git repository in the project directory sets up version control for tracking changes. The command git init is used to create a new Git repository, which involves creating a .git subdirectory containing all necessary metadata and version history.

Staging and Committing Changes:

After initializing the repository, project files need to be added to the staging area, a place where changes are gathered before committing. This is done using the command git add README.md, which stages the README.md file. The subsequent command git commit -m "Initial commit with README.md" creates a commit, which is a snapshot of the project's current state with a message describing the changes. This initial commit serves as the project's starting point.

Connecting to GitHub:

To enable remote collaboration and backup, the local Git repository is connected to a remote repository hosted on GitHub. This involves creating a new repository on GitHub and linking it to the local repository using the git remote add origin <repository_url> command. Finally, the changes are pushed to GitHub using the git push -u origin master command, which uploads the local commits to the remote repository and sets the upstream branch for future pushes.
