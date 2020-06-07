 #**Terms**:  
 - Repository - contains all of the project files and stores each file's revision history 
(ex: on GitHub, click the upper-right corner of the page on the drop-down menu. Select “new repository”, and enter a name of it.)
 - Clone - command line utility which is used to target an existing repository 
(ex: when working with a repository on GitHub, working on a local machine makes it easier. By cloning the repository, you can work on it on your local machine)
- Fork – a copy of a repository- allows you to freely experiment with changed without affecting the original project 
(ex: you can use forks to propose changed related to fixing a bug, rather than logging an issue for a bug you’ve found)
- Branch - is a parallel version of a repository
(ex. creating a branch in your project means you’re creating an environment where you can try out new ideas and those changed won’t affect the master branch)
- Commit - is an individual change to a file 
(ex. you have to explicitly tell Git, which change you want to include in a commit before running the command)
- Merge - takes the changes from one branch and applies them into another
(ex. takes all the commits from the pull requests and adds them to the master branch with a new commit in a merge commit)
- Checkout: a git command for switching between branches in a repository. An example is: say you make a new branch called newImage: git branch newImage, now wanting to make changes to the newImage branch we must first checkout to this branch and then make our commits. Git checkout newImage; git commit;
- Push: The push command is used to upload local repository content to a remote repository in other words transfer commits from the local clone to the remote repository. It is the counterpart to git fetch.
- Pull: the pull command is used to download remote repository content to a local repository. It first runs a fetch command from the specified remote repository and then executes a merge command to merge the remote content into a new local merge commit.
- Remote Add / Remove / Show: Remote add, remove, and show are commands used when dealing with remote repositories. Remote add creates a new remote repository you must also add a shortname to the repository so it appears like: git remote add <shortname> <url>. 
