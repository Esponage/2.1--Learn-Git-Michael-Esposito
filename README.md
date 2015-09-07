Learn Git
Git Introduction

 Read 1.1 About Version Control
 Read 1.2 A Short History of Git
 Read 1.3 Git Basics
 Read 1.4 The Command Line
 Read 1.5 Installing Git
 Ensure that you have followed the Computer Setup instructions from the class notes. If you're not sure, you can run the following commands and make sure they run. If you see command not found, you need to follow the instructions to install the command line tools.

brew --version, should output 0.9.5 or similar
git --version, should output git version 2.5.1 or similar
hub --version, should output hub version 2.2.1 or similar
Git Setup

 Read 1.6 First-Time Git Setup
 Configure git with your name, email, and editor. It is essential that your email address you use with git config matched the email address you used to sign up to GitHub!
 git config --global user.name "<your name>"
 git config --global user.email your@email.com
 git config --global core.editor nano
 Read 1.7 Getting Help
 Read 1.8 Summary
Git Basics

 Read 2.1 Getting a Git Repository
 Use the commands from 2.1 to clone the practice repository from the class page here into your assignments directory.

 Read 2.2 Recording Changes to the Repository

 Create a new file called README.md with the contents "# learn-git"
 Using what you learned from 2.2, stage and commit README.md in the master branch.
 Create a file named IGNOREME.md and setup the git repository to ignore this file so it doesn't show up in the status or get committed.
 Untrack (i.e. make git stop tracking changes to) REMOVEME.md. Verify you did it correctly by adding the text "I should be removed" to REMOVEME.md and make sure that git status does not show the file as modified.
 Rename RENAMEME.md to RENAMED.md in the git repository.

 Read 2.5 Working with Remotes

 Rename the origin remote to upstream
 Create a repository named for the assignment name using the GitHub web interface.
 Copy the git URL from your new repository
 Create a new remote named origin that is pointed at the URL you just copied.
 Push your changes to your repository with git push -u origin master
 Read 2.7 Git Aliases
 Create the 4 aliases (co, br, ci, st) listed at the top of that article.
Hard Mode

 Rename the LOWERCASE.md to lowercase.md. Make sure the change worked by looking at the repository on GitHub.
 Remove the file SECRETS.md so that there is no trace of its contents in the git history.
Further Reading

 Read 2.3 Viewing the Commit History
 Read 2.4 Undoing Things
 Read 2.6 Tagging